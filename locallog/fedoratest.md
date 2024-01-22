```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
22 01 2024 14:43:23.946:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
22 01 2024 14:43:23.948:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
22 01 2024 14:43:23.951:INFO [launcher]: Starting browser Firefox
22 01 2024 14:43:25.756:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket PPI0yfcZdKlR3JVUAAAB with id 20277651
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
22 01 2024 14:43:26.289:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 20277651
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.102 secs)
22 01 2024 14:43:26.406:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 102 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:474 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
22 01 2024 14:43:26.409:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:477 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.133 secs)
22 01 2024 14:43:26.424:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:492 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.146 secs / 0.133 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:506 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.146 secs / 0.133 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.13s.
```
