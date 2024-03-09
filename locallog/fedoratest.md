```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 03 2024 14:07:54.782:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 03 2024 14:07:54.783:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 03 2024 14:07:54.785:INFO [launcher]: Starting browser Firefox
09 03 2024 14:07:56.142:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket qMsm4jEMbA5Schd0AAAB with id 78768650
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 03 2024 14:07:56.526:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 78768650
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.093 secs)
09 03 2024 14:07:56.624:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 93 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:854 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.108 secs)
09 03 2024 14:07:56.648:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:877 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
09 03 2024 14:07:56.653:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:882 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.132 secs / 0.12 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:889 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.132 secs / 0.12 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.32s.
```
