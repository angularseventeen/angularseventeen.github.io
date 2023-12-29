```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 12 2023 14:37:12.362:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 12 2023 14:37:12.364:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 12 2023 14:37:12.367:INFO [launcher]: Starting browser Firefox
29 12 2023 14:37:14.142:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket JGRFg53Z7FIVWRE8AAAB with id 82742421
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 12 2023 14:37:14.656:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 82742421
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.083 secs)
29 12 2023 14:37:14.762:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 83 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:434 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
29 12 2023 14:37:14.765:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:436 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.111 secs)
29 12 2023 14:37:14.790:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:462 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.111 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:469 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.111 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.00s.
```
