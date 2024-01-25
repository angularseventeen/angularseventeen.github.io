```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
25 01 2024 12:45:01.701:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
25 01 2024 12:45:01.703:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
25 01 2024 12:45:01.707:INFO [launcher]: Starting browser Firefox
25 01 2024 12:45:03.809:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket WX0wf5vGB76JcRCDAAAB with id 72585827
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
25 01 2024 12:45:04.363:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 72585827
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.083 secs)
25 01 2024 12:45:04.434:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 83 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:747 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.097 secs)
25 01 2024 12:45:04.486:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:799 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.108 secs)
25 01 2024 12:45:04.497:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:810 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.137 secs / 0.108 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:816 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.137 secs / 0.108 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.87s.
```
