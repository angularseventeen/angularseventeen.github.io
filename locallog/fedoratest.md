```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
31 12 2023 11:22:32.506:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
31 12 2023 11:22:32.508:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
31 12 2023 11:22:32.511:INFO [launcher]: Starting browser Firefox
31 12 2023 11:22:34.280:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket UDY7B22pAJOvwwLfAAAB with id 87656198
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
31 12 2023 11:22:34.797:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 87656198
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.084 secs)
31 12 2023 11:22:34.878:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 84 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:408 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.099 secs)
31 12 2023 11:22:34.893:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:424 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.111 secs)
31 12 2023 11:22:34.932:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:463 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.111 secs)
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
Elapsed Time: 0:2:468 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.111 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.74s.
```
