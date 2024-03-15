```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
14 03 2024 21:38:44.148:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
14 03 2024 21:38:44.149:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
14 03 2024 21:38:44.152:INFO [launcher]: Starting browser Firefox
14 03 2024 21:38:45.431:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket 46b0h5yT2CJRlxc1AAAB with id 54782361
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
14 03 2024 21:38:46.000:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 54782361
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.137 secs)
14 03 2024 21:38:46.159:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 137 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:22 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.151 secs)
14 03 2024 21:38:46.163:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:26 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.164 secs)
14 03 2024 21:38:46.174:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:38 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.176 secs / 0.164 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:42 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.176 secs / 0.164 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 14.75s.
```
