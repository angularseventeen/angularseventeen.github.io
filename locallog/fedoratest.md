```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 01 2024 22:32:34.760:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 01 2024 22:32:34.762:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 01 2024 22:32:34.765:INFO [launcher]: Starting browser Firefox
09 01 2024 22:32:36.545:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket zhxji470cTjnJSxAAAAB with id 36945535
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 01 2024 22:32:37.058:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 36945535
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
09 01 2024 22:32:37.164:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 117 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:440 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.131 secs)
09 01 2024 22:32:37.176:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:452 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.142 secs)
09 01 2024 22:32:37.196:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:473 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.141 secs / 0.142 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:478 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.141 secs / 0.142 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.70s.
```
