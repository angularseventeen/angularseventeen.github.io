```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
10 01 2024 19:05:10.340:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 01 2024 19:05:10.342:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 01 2024 19:05:10.345:INFO [launcher]: Starting browser Firefox
10 01 2024 19:05:12.401:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket DRcH_-Rk-grA8xsGAAAB with id 35932542
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 01 2024 19:05:13.157:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 35932542
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
10 01 2024 19:05:13.301:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 116 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:973 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.136 secs)
10 01 2024 19:05:13.305:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 20 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:977 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.159 secs)
10 01 2024 19:05:13.341:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 23 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:3:12 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.186 secs / 0.159 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:19 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.186 secs / 0.159 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 18.16s.
```
