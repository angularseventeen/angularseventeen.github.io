```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
31 01 2024 18:53:10.075:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
31 01 2024 18:53:10.077:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
31 01 2024 18:53:10.080:INFO [launcher]: Starting browser Firefox
31 01 2024 18:53:11.691:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket t7FVU2Edzogkir0bAAAB with id 24974987
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
31 01 2024 18:53:12.358:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 24974987
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.115 secs)
31 01 2024 18:53:12.498:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 115 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:436 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.134 secs)
31 01 2024 18:53:12.502:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:439 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.156 secs)
31 01 2024 18:53:12.531:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 22 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:468 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.175 secs / 0.156 secs)
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
Elapsed Time: 0:2:473 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.175 secs / 0.156 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 17.37s.
```
