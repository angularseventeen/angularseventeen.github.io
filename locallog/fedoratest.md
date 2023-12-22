```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
22 12 2023 10:12:41.314:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
22 12 2023 10:12:41.316:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
22 12 2023 10:12:41.320:INFO [launcher]: Starting browser Firefox
22 12 2023 10:12:43.127:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket gpPe9K-XpLZdzJZ9AAAB with id 4982196
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
22 12 2023 10:12:43.621:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 4982196
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
22 12 2023 10:12:43.740:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 107 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:460 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
22 12 2023 10:12:43.743:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:462 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.131 secs)
22 12 2023 10:12:43.781:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:500 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.162 secs / 0.131 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:505 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.162 secs / 0.131 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.86s.
```
