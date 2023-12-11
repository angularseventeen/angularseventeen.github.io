```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
11 12 2023 07:30:15.667:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 12 2023 07:30:15.669:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 12 2023 07:30:15.671:INFO [launcher]: Starting browser Firefox
11 12 2023 07:30:16.948:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket psq3HxRKJRwP9C1iAAAB with id 42155110
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 12 2023 07:30:17.380:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 42155110
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
11 12 2023 07:30:17.436:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 77 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:796 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
11 12 2023 07:30:17.451:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:811 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
11 12 2023 07:30:17.471:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:831 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.094 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:835 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.094 secs / 0.103 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.20s.
```
