# RxJS Lite Module #

The Reactive Extensions for JavaScript Lite version is a lightweight version of the Reactive Extensions for JavaScript which covers most of the day to day operators you might use all in a single library.  Functionality such as bridging to events, promises, callbacks, Node.js-style callbacks, time-based operations and more are built right in.

This comes with both `rx.lite.js` which is for use in modern development environments such as > IE9 and server-side environments such as Node.js.  We also have `rx.lite.compat.js` which has backwards compatibility to browsers which do not support all required ES5 features.

## Details ##

Files:
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) 
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- `rx-lite`

NuGet Packages:
- [`RxJS-Lite`](https://www.nuget.org/packages/RxJS-Lite/)

## Included Observable Operators ##

### `Observable Methods`
- [`catch | catchException`](../api/core/operators/catch.md)
- [`concat`](../api/core/operators/concat.md)
- [`create | createWithDisposable`](../api/core/operators/create.md)
- [`defer`](../api/core/operators/defer.md)
- [`empty`](../api/core/operators/empty.md)
- [`from`](../api/core/operators/from.md)
- [`fromArray`](../api/core/operators/fromarray.md)
- [`fromCallback`](../api/core/operators/fromcallback.md)
- [`fromEvent`](../api/core/operators/fromevent.md)
- [`fromEventPattern`](../api/core/operators/fromeventpattern.md)
- [`fromNodeCallback`](../api/core/operators/fromnodecallback.md)
- [`fromPromise`](../api/core/operators/frompromise.md)
- [`interval`](../api/core/operators/interval.md)
- [`just`](../api/core/operators/return.md)
- [`merge`](../api/core/operators/merge.md)
- [`never`](../api/core/operators/never.md)
- [`of`](../api/core/operators/of.md)
- [`ofWithScheduler`](../api/core/operators/ofwithscheduler.md)
- [`range`](../api/core/operators/range.md)
- [`repeat`](../api/core/operators/repeat.md)
- [`return | returnValue`](../api/core/operators/return.md)
- [`throw | throwException`](../api/core/operators/throw.md)
- [`timer`](../api/core/operators/timer.md)
- [`zip`](../api/core/operators/zip.md)
- [`zipArray`](../api/core/operators/ziparray.md)

### `Observable Instance Methods`
- [`asObservable`](../api/core/operators/asobservable.md)
- [`catch | catchException`](../api/core/operators/catchproto.md)
- [`combineLatest`](../api/core/operators/combinelatest.md)
- [`concat`](../api/core/operators/concatproto.md)
- [`concatMap`](../api/core/operators/concatmap.md)
- [`connect`](../api/core/operators/connect.md)
- [`defaultIfEmpty`](../api/core/operators/defaultifempty.md)
- [`delay`](../api/core/operators/delay.md)
- [`delayWithSelector`](../api/core/operators/delaywithselector)
- [`dematerialize`](../api/core/operators/dematerialize)
- [`distinctUntilChanged`](../api/core/operators/distinctuntilchanged.)
- [`do | doAction`](../api/core/operators/do.md)
- [`filter`](../api/core/operators/where.md)
- [`finally | finallyAction`](../api/core/operators/finally.md)
- [`flatMap`](../api/core/operators/selectmany.md)
- [`flatMapLatest`](../api/core/operators/flatmaplatest.md)
- [`ignoreElements`](../api/core/operators/ignoreelements.md)
- [`map`](../api/core/operators/select.md)
- [`merge`](../api/core/operators/mergeproto.md)
- [`mergeObservable | mergeAll`](../api/core/operators/mergeall.md)
- [`multicast`](../api/core/operators/multicast.md)
- [`publish`](../api/core/operators/publish.md)
- [`publishLast`](../api/core/operators/publishlast.md)
- [`publishValue`](../api/core/operators/publishvalue.md)
- [`refCount`](../api/core/operators/refcount.md)
- [`repeat`](../api/core/operators/repeat.md)
- [`replay`](../api/core/operators/replay.md)
- [`retry`](../api/core/operators/retry.md)
- [`sample`](../api/core/operators/sample.md)
- [`scan`](../api/core/operators/scan.md)
- [`select`](../api/core/operators/select.md)
- [`selectConcat`](../api/core/operators/concatmap.md)
- [`selectMany`](../api/core/operators/selectmany.md)
- [`selectSwitch`](../api/core/operators/flatmaplatest.md)
- [`skip`](../api/core/operators/skip.md)
- [`skipLast`](../api/core/operators/skiplast.md)
- [`skipLastWithTime`](../api/core/operators/skiplastwithtime.md)
- [`skipUntil`](../api/core/operators/skipuntil.md)
- [`skipWhile`](../api/core/operators/skipwhile.md)
- [`startWith`](../api/core/operators/startwith.md)
- [`subscribe`](../api/core/operators/subscribe.md)
- [`switch | switchLatest`](../api/core/operators/switch.md)
- [`take`](../api/core/operators/take.md)
- [`takeLast`](../api/core/operators/takelast.md)
- [`takeLastWithTime`](../api/core/operators/takelastwithtime.md)
- [`takeUntil`](../api/core/operators/takeuntil.md)
- [`takeWhile`](../api/core/operators/takewhile.md)
- [`tap`](../api/core/operators/do.md)
- [`throttle`](../api/core/operators/throttle.md)
- [`throttleWithSelector`](../api/core/operators/throttlewithselector.md)
- [`timeout`](../api/core/operators/timeout.md)
- [`timeoutWithSelector`](../api/core/operators/timeoutwithselector.md)
- [`timestamp`](../api/core/operators/timestamp.md)
- [`toArray`](../api/core/operators/toarray.md)
- [`where`](../api/core/operators/where.md)
- [`zip`](../api/core/operators/zipproto.md)

## Included Classes ##

### Core Objects
- [`Rx.Observer`](../api/core/observer.md)
- [`Rx.Notification`](../api/core/notification.md)

### Subjects

- [`Rx.AsyncSubject`](../api/subjects/asyncsubject.md)
- [`Rx.BehaviorSubject`](../api/subjects/behaviorsubject.md)
- [`Rx.ReplaySubject`](../api/subjects/replaysubject.md)
- [`Rx.Subject`](../api/subjects/subject.md)

### Schedulers

- [`Rx.Scheduler`](../api/schedulers/scheduler.md)

### Disposables

- [`Rx.CompositeDisposable`](../api/disposables/compositedisposable.md)
- [`Rx.Disposable`](../api/disposables/disposable.md)
- [`Rx.RefCountDisposable`](../api/disposables/refcountdisposable.md)
- [`Rx.SerialDisposable`](../api/disposables/serialdisposable.md)
- [`Rx.SingleAssignmentDisposable`](../api/disposables/singleassignmentdisposable.md)
