```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
02 02 2024 05:06:51.504:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
02 02 2024 05:06:51.506:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
02 02 2024 05:06:51.510:INFO [launcher]: Starting browser Firefox
02 02 2024 05:06:53.205:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket Xt8PnxGpN_yrwpFtAAAB with id 40125222
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
02 02 2024 05:06:54.489:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 40125222
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
02 02 2024 05:06:54.502:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 114 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:3:13 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.131 secs)
02 02 2024 05:06:54.505:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:3:15 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.15 secs)
02 02 2024 05:06:54.506:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:3:16 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.019 secs / 0.15 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:20 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.019 secs / 0.15 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 11.37s.
```
