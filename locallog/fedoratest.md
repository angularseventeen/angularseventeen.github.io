```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
25 02 2024 20:43:49.430:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
25 02 2024 20:43:49.432:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
25 02 2024 20:43:49.434:INFO [launcher]: Starting browser Firefox
25 02 2024 20:43:50.784:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket voAv1NT41V4NyoiHAAAB with id 14219278
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
25 02 2024 20:43:51.156:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 14219278
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.079 secs)
25 02 2024 20:43:51.233:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 79 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:814 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
25 02 2024 20:43:51.253:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:833 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.102 secs)
25 02 2024 20:43:51.275:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:856 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.102 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:860 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.102 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.96s.
```
