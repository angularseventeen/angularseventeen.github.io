```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 01 2024 19:58:43.892:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 01 2024 19:58:43.894:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 01 2024 19:58:43.898:INFO [launcher]: Starting browser Firefox
09 01 2024 19:58:45.734:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket M1D8VliltDT1HGucAAAB with id 89806988
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 01 2024 19:58:46.274:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 89806988
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.088 secs)
09 01 2024 19:58:46.357:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 88 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:484 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
09 01 2024 19:58:46.392:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:519 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.119 secs)
09 01 2024 19:58:46.409:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:536 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.137 secs / 0.119 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:541 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.137 secs / 0.119 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.91s.
```
