```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
06 01 2024 17:13:37.921:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
06 01 2024 17:13:37.922:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
06 01 2024 17:13:37.925:INFO [launcher]: Starting browser Firefox
06 01 2024 17:13:39.747:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket ZuL1pR_Od81Qkl3pAAAB with id 19346606
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
06 01 2024 17:13:40.463:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 19346606
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.127 secs)
06 01 2024 17:13:40.603:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 127 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:693 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.15 secs)
06 01 2024 17:13:40.619:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 23 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:709 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.165 secs)
06 01 2024 17:13:40.650:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:740 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.212 secs / 0.165 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:768 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.212 secs / 0.165 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 16.46s.
```
