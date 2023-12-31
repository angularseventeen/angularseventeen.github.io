```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 12 2023 21:18:51.986:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 12 2023 21:18:51.988:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 12 2023 21:18:51.990:INFO [launcher]: Starting browser Firefox
30 12 2023 21:18:53.755:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket RHZe2n2XJcypvleIAAAB with id 78287060
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 12 2023 21:18:54.262:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 78287060
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.124 secs)
30 12 2023 21:18:54.370:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 124 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:417 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.142 secs)
30 12 2023 21:18:54.421:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:468 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.156 secs)
30 12 2023 21:18:54.422:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:470 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.162 secs / 0.156 secs)
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
Elapsed Time: 0:2:474 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.162 secs / 0.156 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.69s.
```
