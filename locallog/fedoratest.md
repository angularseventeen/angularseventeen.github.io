```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 01 2024 15:15:13.144:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 01 2024 15:15:13.147:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 01 2024 15:15:13.152:INFO [launcher]: Starting browser Firefox
12 01 2024 15:15:14.913:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket -Z3kR3ta97pIsdBnAAAB with id 25074132
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 01 2024 15:15:15.463:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 25074132
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
12 01 2024 15:15:15.554:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:435 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
12 01 2024 15:15:15.587:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:467 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
12 01 2024 15:15:15.595:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:475 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.116 secs)
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
Elapsed Time: 0:2:481 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.84s.
```
