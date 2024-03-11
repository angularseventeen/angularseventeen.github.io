```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
11 03 2024 08:42:50.012:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 03 2024 08:42:50.013:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 03 2024 08:42:50.016:INFO [launcher]: Starting browser Firefox
11 03 2024 08:42:51.385:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket NzaLW2R0s-y43HJtAAAB with id 25985681
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 03 2024 08:42:51.854:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 25985681
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.083 secs)
11 03 2024 08:42:51.933:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 83 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:933 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
11 03 2024 08:42:51.950:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:949 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.105 secs)
11 03 2024 08:42:51.968:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:967 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.116 secs / 0.105 secs)
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
Elapsed Time: 0:1:972 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.116 secs / 0.105 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 11.05s.
```
