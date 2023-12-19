```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 12 2023 12:03:48.010:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 12 2023 12:03:48.012:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 12 2023 12:03:48.016:INFO [launcher]: Starting browser Firefox
19 12 2023 12:03:49.747:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket BBOvwW1C6WD5v0efAAAB with id 71586085
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 12 2023 12:03:50.228:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 71586085
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
19 12 2023 12:03:50.334:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 98 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:359 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.11 secs)
19 12 2023 12:03:50.341:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:366 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.124 secs)
19 12 2023 12:03:50.348:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:372 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.124 secs)
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
Elapsed Time: 0:2:391 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.124 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.71s.
```
