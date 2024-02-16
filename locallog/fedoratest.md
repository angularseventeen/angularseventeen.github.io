```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
16 02 2024 07:42:17.934:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 02 2024 07:42:17.936:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 02 2024 07:42:17.939:INFO [launcher]: Starting browser Firefox
16 02 2024 07:42:19.764:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket EPOwajUzEeFXRFIZAAAB with id 51474170
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 02 2024 07:42:20.283:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 51474170
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.105 secs)
16 02 2024 07:42:20.375:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 105 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:456 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.127 secs)
16 02 2024 07:42:20.398:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 22 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:480 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.143 secs)
16 02 2024 07:42:20.441:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:523 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.161 secs / 0.143 secs)
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
Elapsed Time: 0:2:528 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.161 secs / 0.143 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.26s.
```
