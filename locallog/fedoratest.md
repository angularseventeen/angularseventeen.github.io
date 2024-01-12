```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
11 01 2024 22:08:50.427:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 01 2024 22:08:50.430:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 01 2024 22:08:50.434:INFO [launcher]: Starting browser Firefox
11 01 2024 22:08:52.187:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket nNW6MGedAd5QIDy-AAAB with id 33578131
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 01 2024 22:08:52.711:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 33578131
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.092 secs)
11 01 2024 22:08:52.796:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 92 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:394 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.104 secs)
11 01 2024 22:08:52.809:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:407 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
11 01 2024 22:08:52.822:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:420 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.114 secs)
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
Elapsed Time: 0:2:425 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.90s.
```
