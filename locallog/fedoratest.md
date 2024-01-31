```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
31 01 2024 12:00:58.804:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
31 01 2024 12:00:58.806:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
31 01 2024 12:00:58.809:INFO [launcher]: Starting browser Firefox
31 01 2024 12:01:00.625:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 42Ga5SPitGx3oR1_AAAB with id 79685284
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
31 01 2024 12:01:01.132:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 79685284
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.093 secs)
31 01 2024 12:01:01.224:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 93 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:435 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.109 secs)
31 01 2024 12:01:01.261:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:471 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
31 01 2024 12:01:01.273:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:483 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.12 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:489 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.12 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.37s.
```
