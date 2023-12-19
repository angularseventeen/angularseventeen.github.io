```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 12 2023 17:09:29.490:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 12 2023 17:09:29.492:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 12 2023 17:09:29.496:INFO [launcher]: Starting browser Firefox
19 12 2023 17:09:31.253:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket gwPx8TidLsXLQzBtAAAB with id 32425966
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 12 2023 17:09:31.791:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 32425966
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
19 12 2023 17:09:31.879:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 103 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:402 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
19 12 2023 17:09:31.910:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:433 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.13 secs)
19 12 2023 17:09:31.919:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:442 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.13 secs / 0.13 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:447 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.13 secs / 0.13 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.03s.
```
