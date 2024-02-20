```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
20 02 2024 09:29:01.076:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
20 02 2024 09:29:01.078:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
20 02 2024 09:29:01.081:INFO [launcher]: Starting browser Firefox
20 02 2024 09:29:02.797:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket eVdqPPBLVax0j02vAAAB with id 282286
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
20 02 2024 09:29:03.350:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 282286
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.122 secs)
20 02 2024 09:29:03.475:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 122 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:420 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.14 secs)
20 02 2024 09:29:03.488:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:433 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.152 secs)
20 02 2024 09:29:03.500:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:444 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.152 secs / 0.152 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:449 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.152 secs / 0.152 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.13s.
```
