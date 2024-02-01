```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
01 02 2024 12:49:03.562:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
01 02 2024 12:49:03.564:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
01 02 2024 12:49:03.568:INFO [launcher]: Starting browser Firefox
01 02 2024 12:49:05.242:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 6QGXmq87MDYJ0rgwAAAB with id 5919874
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
01 02 2024 12:49:05.756:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 5919874
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
01 02 2024 12:49:05.862:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:316 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.102 secs)
01 02 2024 12:49:05.865:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:318 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.115 secs)
01 02 2024 12:49:05.896:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:349 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.115 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:355 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.115 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.42s.
```
