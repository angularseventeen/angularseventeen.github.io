```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 12 2023 15:22:42.442:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 12 2023 15:22:42.444:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 12 2023 15:22:42.446:INFO [launcher]: Starting browser Firefox
19 12 2023 15:22:44.220:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket bR7QuQQ2_eS1H4s8AAAB with id 27197837
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 12 2023 15:22:44.694:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 27197837
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
19 12 2023 15:22:44.793:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 89 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:385 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.106 secs)
19 12 2023 15:22:44.810:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:402 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.123 secs)
19 12 2023 15:22:44.838:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:429 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.148 secs / 0.123 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:436 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.148 secs / 0.123 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.78s.
```
