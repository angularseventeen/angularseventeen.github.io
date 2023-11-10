```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
10 11 2023 09:02:47.602:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 11 2023 09:02:47.604:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 11 2023 09:02:47.605:INFO [launcher]: Starting browser Firefox
10 11 2023 09:02:48.822:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket twxwncUqLVUAth0xAAAB with id 87310465
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 11 2023 09:02:49.190:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 87310465
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.064 secs)
10 11 2023 09:02:49.252:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 64 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:660 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
10 11 2023 09:02:49.272:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:680 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.086 secs)
10 11 2023 09:02:49.285:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:694 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.096 secs / 0.086 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:697 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.096 secs / 0.086 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.96s.
```
