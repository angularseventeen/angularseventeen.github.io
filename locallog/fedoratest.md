```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 01 2024 22:49:53.530:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 01 2024 22:49:53.532:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 01 2024 22:49:53.537:INFO [launcher]: Starting browser Firefox
29 01 2024 22:49:55.055:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 3nwM0SL29aYMr-r3AAAB with id 65450621
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 01 2024 22:49:55.545:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 65450621
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.081 secs)
29 01 2024 22:49:55.641:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 81 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:130 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.094 secs)
29 01 2024 22:49:55.658:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:146 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.104 secs)
29 01 2024 22:49:55.660:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:148 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.123 secs / 0.104 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:159 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.123 secs / 0.104 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.99s.
```
