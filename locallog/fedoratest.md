```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
31 01 2024 23:21:33.284:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
31 01 2024 23:21:33.286:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
31 01 2024 23:21:33.289:INFO [launcher]: Starting browser Firefox
31 01 2024 23:21:34.836:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 7dukRQIpdWefjHCRAAAB with id 24685479
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
31 01 2024 23:21:35.318:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 24685479
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.078 secs)
31 01 2024 23:21:35.394:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 78 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:125 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
31 01 2024 23:21:35.407:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:137 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
31 01 2024 23:21:35.436:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:167 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.121 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:171 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.121 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.78s.
```
