```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
11 01 2024 11:28:58.676:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 01 2024 11:28:58.678:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 01 2024 11:28:58.682:INFO [launcher]: Starting browser Firefox
11 01 2024 11:29:00.423:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket Pi8SBvZODUXt40BcAAAB with id 39035104
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 01 2024 11:29:00.915:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 39035104
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
11 01 2024 11:29:00.993:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:331 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
11 01 2024 11:29:01.028:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:366 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
11 01 2024 11:29:01.038:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:377 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.126 secs / 0.114 secs)
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
Elapsed Time: 0:2:383 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.126 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.88s.
```
