```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 12 2023 09:11:04.188:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 12 2023 09:11:04.191:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 12 2023 09:11:04.193:INFO [launcher]: Starting browser Firefox
30 12 2023 09:11:05.918:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket m_C0FJEcuNVmmHIEAAAB with id 51030015
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 12 2023 09:11:06.435:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 51030015
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.111 secs)
30 12 2023 09:11:06.564:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 111 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:401 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.124 secs)
30 12 2023 09:11:06.567:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:403 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.138 secs)
30 12 2023 09:11:06.598:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:435 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.166 secs / 0.138 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:439 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.166 secs / 0.138 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.84s.
```
