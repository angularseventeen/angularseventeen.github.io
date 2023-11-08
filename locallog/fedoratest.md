```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
08 11 2023 16:20:36.443:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 11 2023 16:20:36.445:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 11 2023 16:20:36.454:INFO [launcher]: Starting browser Firefox
08 11 2023 16:20:37.885:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket 0GRuTepWfFyKK6cOAAAB with id 97895253
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 11 2023 16:20:38.299:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 97895253
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.081 secs)
08 11 2023 16:20:38.386:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 81 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:962 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
08 11 2023 16:20:38.401:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'angularseventeengithubio' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:978 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'angularseventeengithubio' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
08 11 2023 16:20:38.419:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:995 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.123 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'angularseventeengithubio' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:0 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.123 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.04s.
```
