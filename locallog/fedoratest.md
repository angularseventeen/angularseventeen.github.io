```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
10 11 2023 00:16:56.440:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 11 2023 00:16:56.442:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 11 2023 00:16:56.446:INFO [launcher]: Starting browser Firefox
10 11 2023 00:16:57.678:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket IqfPb8x1d8i9wSL4AAAB with id 89453357
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 11 2023 00:16:58.071:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 89453357
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.059 secs)
10 11 2023 00:16:58.134:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 59 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:713 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.069 secs)
10 11 2023 00:16:58.141:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:720 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.076 secs)
10 11 2023 00:16:58.152:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 7 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:731 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.083 secs / 0.076 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:735 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.083 secs / 0.076 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.30s.
```
