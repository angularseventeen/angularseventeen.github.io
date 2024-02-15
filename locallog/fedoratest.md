```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
14 02 2024 22:38:37.118:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
14 02 2024 22:38:37.120:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
14 02 2024 22:38:37.123:INFO [launcher]: Starting browser Firefox
14 02 2024 22:38:38.670:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket yVXwLxC8lPNUiRmsAAAB with id 25032816
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
14 02 2024 22:38:39.133:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 25032816
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.083 secs)
14 02 2024 22:38:39.220:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 83 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:122 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
14 02 2024 22:38:39.234:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:135 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.11 secs)
14 02 2024 22:38:39.253:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:155 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.152 secs / 0.11 secs)
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
Elapsed Time: 0:2:190 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.152 secs / 0.11 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.87s.
```
