```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
16 03 2024 10:22:48.148:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 03 2024 10:22:48.150:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 03 2024 10:22:48.152:INFO [launcher]: Starting browser Firefox
16 03 2024 10:22:49.414:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket tm56v_HHEdI1AcRhAAAB with id 13123332
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 03 2024 10:22:49.793:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 13123332
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.096 secs)
16 03 2024 10:22:49.886:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 96 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:748 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.112 secs)
16 03 2024 10:22:49.908:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:769 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.123 secs)
16 03 2024 10:22:49.920:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:781 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.128 secs / 0.123 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:784 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.128 secs / 0.123 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.33s.
```
