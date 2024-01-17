```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
17 01 2024 07:54:14.293:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
17 01 2024 07:54:14.295:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
17 01 2024 07:54:14.298:INFO [launcher]: Starting browser Firefox
17 01 2024 07:54:16.220:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket 56_DbjREKYNoinBPAAAB with id 81908394
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
17 01 2024 07:54:17.690:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 81908394
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
17 01 2024 07:54:17.707:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 120 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:3:426 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.134 secs)
17 01 2024 07:54:17.710:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:3:428 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.148 secs)
17 01 2024 07:54:17.711:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:3:429 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.023 secs / 0.148 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:436 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.023 secs / 0.148 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 11.97s.
```
