```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
31 01 2024 04:30:00.568:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
31 01 2024 04:30:00.570:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
31 01 2024 04:30:00.573:INFO [launcher]: Starting browser Firefox
31 01 2024 04:30:02.308:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket R_CALOZLkxU1exjIAAAB with id 57666993
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
31 01 2024 04:30:02.886:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 57666993
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.097 secs)
31 01 2024 04:30:02.967:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 97 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:415 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.113 secs)
31 01 2024 04:30:02.982:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:430 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.125 secs)
31 01 2024 04:30:03.005:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:453 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.125 secs)
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
Elapsed Time: 0:2:458 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.125 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.33s.
```
