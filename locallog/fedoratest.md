```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 12 2023 10:03:06.695:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 12 2023 10:03:06.697:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 12 2023 10:03:06.701:INFO [launcher]: Starting browser Firefox
30 12 2023 10:03:08.471:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket ROhEzOya1OGLtGFlAAAB with id 44200022
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 12 2023 10:03:09.036:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 44200022
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
30 12 2023 10:03:09.125:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 89 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:464 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.105 secs)
30 12 2023 10:03:09.136:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:474 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
30 12 2023 10:03:09.145:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:483 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.112 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:489 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.112 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.92s.
```
