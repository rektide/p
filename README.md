[![Build Status](https://secure.travis-ci.org/rkatic/p.png)](http://travis-ci.org/rkatic/p)

#P

A simple Promises/A+ library.

- A subset of the [Q](https://github.com/kriskowal/q) library.
- Passing the [Promises/A+ Compliance Test Suite](https://github.com/promises-aplus/promises-tests).
- Small.
- Fast.

##API

P is a subset of [Q](https://github.com/kriskowal/q).

- `P(val)` same as `P.resolve(val)`
- `P.reject(reason)`
- `P.defer()`
- `P.all(promises)`
- `P.onerror`
- `P.nextTick(callback)`
- `deferred.promise`
- `deferred.fulfill(value)`
- `deferred.reject(reason)`
- `promise.then(onFulfilled, onRejected)`
- `promise.done(onFulfilled, onRejected)`
- `promise.spread(onFulfilled, onRejected)`