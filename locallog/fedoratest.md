```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
08 11 2023 16:19:03.355:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 11 2023 16:19:03.357:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 11 2023 16:19:03.360:INFO [launcher]: Starting browser Firefox
08 11 2023 16:19:04.892:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket ZnBuaa0WJpoSIeh_AAAB with id 70473811
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 11 2023 16:19:05.252:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 70473811
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.07 secs)
08 11 2023 16:19:05.325:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 70 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:990 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.08 secs)
08 11 2023 16:19:05.336:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'angularseventeengithubio' title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:1 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'angularseventeengithubio' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
08 11 2023 16:19:05.345:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:10 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.102 secs / 0.089 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'angularseventeengithubio' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:22 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.102 secs / 0.089 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.65s.
```
