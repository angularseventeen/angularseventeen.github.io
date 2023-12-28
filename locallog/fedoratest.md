```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
28 12 2023 12:02:42.490:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
28 12 2023 12:02:42.492:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
28 12 2023 12:02:42.495:INFO [launcher]: Starting browser Firefox
28 12 2023 12:02:44.597:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket sGaGwB00I0aOfE9VAAAB with id 29639700
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
28 12 2023 12:02:45.807:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 29639700
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.165 secs)
28 12 2023 12:02:45.827:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 165 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:3:348 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.179 secs)
28 12 2023 12:02:45.829:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:3:350 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.195 secs)
28 12 2023 12:02:45.830:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:3:351 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.024 secs / 0.195 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:356 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.024 secs / 0.195 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 11.80s.
```
