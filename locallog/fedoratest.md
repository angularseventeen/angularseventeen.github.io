```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 12 2023 07:22:26.289:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 12 2023 07:22:26.291:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 12 2023 07:22:26.293:INFO [launcher]: Starting browser Firefox
30 12 2023 07:22:28.080:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket TPE1hhZeY3atDFkbAAAB with id 3809865
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 12 2023 07:22:28.608:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 3809865
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.093 secs)
30 12 2023 07:22:28.689:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 93 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:433 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.109 secs)
30 12 2023 07:22:28.706:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:449 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.122 secs)
30 12 2023 07:22:28.749:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:492 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.122 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:496 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.143 secs / 0.122 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.60s.
```
