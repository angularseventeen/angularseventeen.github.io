```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
27 11 2023 10:40:47.449:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
27 11 2023 10:40:47.450:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
27 11 2023 10:40:47.453:INFO [launcher]: Starting browser Firefox
27 11 2023 10:40:48.782:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket 2RgXeZK-CHKAQA0nAAAB with id 9874877
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
27 11 2023 10:40:49.209:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 9874877
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.092 secs)
27 11 2023 10:40:49.306:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 92 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:868 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.104 secs)
27 11 2023 10:40:49.353:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:915 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
27 11 2023 10:40:49.354:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:916 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.146 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:919 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.146 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.94s.
```
