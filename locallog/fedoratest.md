```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
04 03 2024 07:00:01.587:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
04 03 2024 07:00:01.589:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
04 03 2024 07:00:01.593:INFO [launcher]: Starting browser Firefox
04 03 2024 07:00:03.326:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket x_7jSgJVffc1l0sdAAAB with id 19184889
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
04 03 2024 07:00:03.773:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 19184889
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
04 03 2024 07:00:03.852:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 77 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:289 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
04 03 2024 07:00:03.872:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:309 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.1 secs)
04 03 2024 07:00:03.889:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:326 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.117 secs / 0.1 secs)
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
Elapsed Time: 0:2:330 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.117 secs / 0.1 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.28s.
```
