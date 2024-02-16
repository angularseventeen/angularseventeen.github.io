```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
16 02 2024 08:52:08.861:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 02 2024 08:52:08.864:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 02 2024 08:52:08.868:INFO [launcher]: Starting browser Firefox
16 02 2024 08:52:10.612:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket Cic3VfkUYT6ga-fSAAAB with id 43349072
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 02 2024 08:52:11.181:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 43349072
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
16 02 2024 08:52:11.296:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 90 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:460 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
16 02 2024 08:52:11.299:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:462 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.112 secs)
16 02 2024 08:52:11.300:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:463 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.112 secs)
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
Elapsed Time: 0:2:467 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.112 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.34s.
```
