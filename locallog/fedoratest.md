```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
03 01 2024 03:14:16.158:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
03 01 2024 03:14:16.160:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
03 01 2024 03:14:16.164:INFO [launcher]: Starting browser Firefox
03 01 2024 03:14:17.997:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket SdQS72QntUlL02YnAAAB with id 6104366
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
03 01 2024 03:14:18.519:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 6104366
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.082 secs)
03 01 2024 03:14:18.613:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 82 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:488 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
03 01 2024 03:14:18.615:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:490 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.11 secs)
03 01 2024 03:14:18.649:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:525 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.11 secs)
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
Elapsed Time: 0:2:530 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.11 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.29s.
```
