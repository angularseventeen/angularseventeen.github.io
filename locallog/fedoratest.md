```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 01 2024 21:21:07.544:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 01 2024 21:21:07.546:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 01 2024 21:21:07.549:INFO [launcher]: Starting browser Firefox
09 01 2024 21:21:09.340:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket HiA62Ya2eL42Ubf6AAAB with id 91412280
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 01 2024 21:21:09.849:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 91412280
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.121 secs)
09 01 2024 21:21:09.980:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 121 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:451 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.138 secs)
09 01 2024 21:21:10.010:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:481 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.153 secs)
09 01 2024 21:21:10.014:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:485 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.168 secs / 0.153 secs)
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
Elapsed Time: 0:2:490 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.168 secs / 0.153 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.91s.
```
