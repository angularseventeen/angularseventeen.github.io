```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
03 01 2024 15:23:36.686:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
03 01 2024 15:23:36.687:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
03 01 2024 15:23:36.690:INFO [launcher]: Starting browser Firefox
03 01 2024 15:23:38.530:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket LWAGUPa0jzJ4jrj4AAAB with id 69433170
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
03 01 2024 15:23:39.223:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 69433170
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.126 secs)
03 01 2024 15:23:39.380:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 126 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:707 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.15 secs)
03 01 2024 15:23:39.402:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 24 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:729 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.167 secs)
03 01 2024 15:23:39.409:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:735 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.188 secs / 0.167 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:740 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.188 secs / 0.167 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 16.43s.
```
