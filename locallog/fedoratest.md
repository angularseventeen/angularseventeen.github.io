```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
01 02 2024 14:24:49.341:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
01 02 2024 14:24:49.343:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
01 02 2024 14:24:49.347:INFO [launcher]: Starting browser Firefox
01 02 2024 14:24:51.114:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket HSckJoF51x8-9-wuAAAB with id 77258464
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
01 02 2024 14:24:51.637:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 77258464
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.079 secs)
01 02 2024 14:24:51.723:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 79 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:397 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.097 secs)
01 02 2024 14:24:51.754:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:428 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.108 secs)
01 02 2024 14:24:51.755:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:429 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.119 secs / 0.108 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:435 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.119 secs / 0.108 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.56s.
```
