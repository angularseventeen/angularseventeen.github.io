```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
20 11 2023 12:16:29.788:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
20 11 2023 12:16:29.790:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
20 11 2023 12:16:29.793:INFO [launcher]: Starting browser Firefox
20 11 2023 12:16:31.003:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket mRV7WAtyzCDAGmBaAAAB with id 6069069
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
20 11 2023 12:16:31.290:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 6069069
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.068 secs)
20 11 2023 12:16:31.360:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 68 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:591 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.076 secs)
20 11 2023 12:16:31.366:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:597 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.082 secs)
20 11 2023 12:16:31.379:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 6 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:611 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.092 secs / 0.082 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:615 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.092 secs / 0.082 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.03s.
```
