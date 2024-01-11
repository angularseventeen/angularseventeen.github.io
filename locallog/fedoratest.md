```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
10 01 2024 19:44:50.886:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 01 2024 19:44:50.888:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 01 2024 19:44:50.892:INFO [launcher]: Starting browser Firefox
10 01 2024 19:44:53.078:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket UJ9ziJ2tPMoqqEA5AAAB with id 69658225
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 01 2024 19:44:53.698:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 69658225
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.086 secs)
10 01 2024 19:44:53.792:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 86 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:921 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
10 01 2024 19:44:53.799:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:927 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
10 01 2024 19:44:53.813:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:942 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.117 secs)
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
Elapsed Time: 0:2:953 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.122 secs / 0.117 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.43s.
```
