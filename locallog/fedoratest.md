```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
05 03 2024 06:26:31.746:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
05 03 2024 06:26:31.748:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
05 03 2024 06:26:31.751:INFO [launcher]: Starting browser Firefox
05 03 2024 06:26:33.490:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket je_7cXeOsuwkFoA_AAAB with id 58739185
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
05 03 2024 06:26:34.197:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 58739185
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
05 03 2024 06:26:34.302:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 101 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:581 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.118 secs)
05 03 2024 06:26:34.343:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:622 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.136 secs)
05 03 2024 06:26:34.371:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:650 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.175 secs / 0.136 secs)
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
Elapsed Time: 0:2:656 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.175 secs / 0.136 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.37s.
```
