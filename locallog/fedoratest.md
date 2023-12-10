```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
10 12 2023 01:33:10.289:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 12 2023 01:33:10.291:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 12 2023 01:33:10.294:INFO [launcher]: Starting browser Firefox
10 12 2023 01:33:11.551:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket AezL3GCXtWsnGwyjAAAB with id 49652325
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 12 2023 01:33:11.895:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 49652325
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.052 secs)
10 12 2023 01:33:11.959:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 52 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:679 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.066 secs)
10 12 2023 01:33:11.964:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:684 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.073 secs)
10 12 2023 01:33:11.977:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 7 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:698 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.073 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:705 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.073 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.16s.
```
