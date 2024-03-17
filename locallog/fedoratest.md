```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
17 03 2024 10:31:04.845:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
17 03 2024 10:31:04.846:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
17 03 2024 10:31:04.849:INFO [launcher]: Starting browser Firefox
17 03 2024 10:31:06.216:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket Yj1YrEQ_ljHLplKEAAAB with id 22999075
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
17 03 2024 10:31:06.768:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 22999075
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.071 secs)
17 03 2024 10:31:06.832:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 71 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:998 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
17 03 2024 10:31:06.852:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:19 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
17 03 2024 10:31:06.858:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:24 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.091 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:28 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.091 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.59s.
```
