```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 11 2023 21:46:23.049:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 11 2023 21:46:23.051:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 11 2023 21:46:23.054:INFO [launcher]: Starting browser Firefox
29 11 2023 21:46:24.669:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket YELvU0wGZb5LNydUAAAB with id 82241713
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 11 2023 21:46:24.983:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 82241713
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.058 secs)
29 11 2023 21:46:25.039:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 58 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:15 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.067 secs)
29 11 2023 21:46:25.050:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:25 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
29 11 2023 21:46:25.060:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:36 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.081 secs / 0.077 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:42 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.081 secs / 0.077 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.53s.
```
