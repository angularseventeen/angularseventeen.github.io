```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
27 02 2024 23:08:45.872:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
27 02 2024 23:08:45.874:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
27 02 2024 23:08:45.877:INFO [launcher]: Starting browser Firefox
27 02 2024 23:08:47.482:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket psss-IjANHhDCGWAAAAB with id 71928610
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
27 02 2024 23:08:48.087:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 71928610
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
27 02 2024 23:08:48.198:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 101 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:338 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
27 02 2024 23:08:48.239:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:378 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.132 secs)
27 02 2024 23:08:48.240:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:379 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.155 secs / 0.132 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:385 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.155 secs / 0.132 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 14.94s.
```
