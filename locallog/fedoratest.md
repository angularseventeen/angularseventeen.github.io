```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
20 12 2023 15:45:04.345:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
20 12 2023 15:45:04.347:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
20 12 2023 15:45:04.350:INFO [launcher]: Starting browser Firefox
20 12 2023 15:45:06.150:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket 89DT3yQ2zokyngNiAAAB with id 64355583
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
20 12 2023 15:45:06.642:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 64355583
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
20 12 2023 15:45:06.771:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 107 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:460 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.121 secs)
20 12 2023 15:45:06.774:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:463 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.138 secs)
20 12 2023 15:45:06.793:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:481 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.154 secs / 0.138 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:487 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.154 secs / 0.138 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.08s.
```
