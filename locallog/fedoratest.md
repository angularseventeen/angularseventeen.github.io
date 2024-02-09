```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
08 02 2024 20:12:18.499:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 02 2024 20:12:18.501:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 02 2024 20:12:18.504:INFO [launcher]: Starting browser Firefox
08 02 2024 20:12:20.048:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket bmzyTUR7pkr98bOnAAAB with id 45471929
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 02 2024 20:12:20.953:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 45471929
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
08 02 2024 20:12:21.101:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 120 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:615 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.144 secs)
08 02 2024 20:12:21.108:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 24 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:622 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.16 secs)
08 02 2024 20:12:21.134:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:648 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.183 secs / 0.16 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:653 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.183 secs / 0.16 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 16.86s.
```
