```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
25 11 2023 14:25:01.944:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
25 11 2023 14:25:01.946:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
25 11 2023 14:25:01.949:INFO [launcher]: Starting browser Firefox
25 11 2023 14:25:03.200:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket u0GpD8Pib3olL_g-AAAB with id 12117642
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
25 11 2023 14:25:03.480:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 12117642
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.067 secs)
25 11 2023 14:25:03.552:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 67 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:632 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.079 secs)
25 11 2023 14:25:03.567:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:647 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.085 secs)
25 11 2023 14:25:03.573:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 6 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:653 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.107 secs / 0.085 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:670 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.107 secs / 0.085 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.33s.
```
