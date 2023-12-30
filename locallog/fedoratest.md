```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 12 2023 08:12:36.641:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 12 2023 08:12:36.643:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 12 2023 08:12:36.646:INFO [launcher]: Starting browser Firefox
30 12 2023 08:12:38.461:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket EK3E6pc-IaqvDt5eAAAB with id 30880990
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 12 2023 08:12:39.019:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 30880990
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.091 secs)
30 12 2023 08:12:39.109:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 91 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:502 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.109 secs)
30 12 2023 08:12:39.126:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:519 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.121 secs)
30 12 2023 08:12:39.136:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:528 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.121 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:538 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.121 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.04s.
```
