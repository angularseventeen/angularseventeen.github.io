```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 01 2024 17:17:40.190:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 01 2024 17:17:40.193:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 01 2024 17:17:40.197:INFO [launcher]: Starting browser Firefox
30 01 2024 17:17:41.938:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket xvjxZ5i7MsAflhiLAAAB with id 19047449
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 01 2024 17:17:42.470:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 19047449
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.088 secs)
30 01 2024 17:17:42.559:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 88 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:388 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.1 secs)
30 01 2024 17:17:42.561:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:390 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
30 01 2024 17:17:42.571:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:400 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.115 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:418 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.115 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.78s.
```
