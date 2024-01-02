```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
02 01 2024 18:48:29.301:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
02 01 2024 18:48:29.303:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
02 01 2024 18:48:29.306:INFO [launcher]: Starting browser Firefox
02 01 2024 18:48:31.173:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket Je7kbp5_SO6xSEvvAAAB with id 20530166
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
02 01 2024 18:48:31.731:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 20530166
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
02 01 2024 18:48:31.811:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 90 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:544 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
02 01 2024 18:48:31.816:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:550 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
02 01 2024 18:48:31.826:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:560 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.112 secs / 0.12 secs)
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
Elapsed Time: 0:2:579 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.112 secs / 0.12 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.78s.
```
