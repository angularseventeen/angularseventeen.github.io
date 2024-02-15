```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
15 02 2024 06:58:37.377:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
15 02 2024 06:58:37.379:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
15 02 2024 06:58:37.381:INFO [launcher]: Starting browser Firefox
15 02 2024 06:58:38.911:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket uFUD5eabOBSmr9FEAAAB with id 78523694
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
15 02 2024 06:58:39.392:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 78523694
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.076 secs)
15 02 2024 06:58:39.471:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 76 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:130 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.091 secs)
15 02 2024 06:58:39.490:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:148 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.102 secs)
15 02 2024 06:58:39.491:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:149 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.101 secs / 0.102 secs)
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
Elapsed Time: 0:2:153 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.101 secs / 0.102 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.62s.
```
