```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 01 2024 12:07:50.369:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 01 2024 12:07:50.372:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 01 2024 12:07:50.376:INFO [launcher]: Starting browser Firefox
12 01 2024 12:07:52.137:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket knFM3jOixg-HHYhAAAAB with id 47484511
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 01 2024 12:07:52.655:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 47484511
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.097 secs)
12 01 2024 12:07:52.739:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 97 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:395 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
12 01 2024 12:07:52.771:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 20 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:427 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.13 secs)
12 01 2024 12:07:52.786:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:442 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.13 secs)
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
Elapsed Time: 0:2:447 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.13 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.13s.
```
