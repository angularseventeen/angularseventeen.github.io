```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
16 03 2024 10:34:49.925:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 03 2024 10:34:49.927:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 03 2024 10:34:49.929:INFO [launcher]: Starting browser Firefox
16 03 2024 10:34:51.195:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket OoNZ4AIo7Zm1I5yLAAAB with id 155224
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 03 2024 10:34:51.568:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 155224
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
16 03 2024 10:34:51.667:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 98 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:752 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.113 secs)
16 03 2024 10:34:51.684:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:769 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.126 secs)
16 03 2024 10:34:51.706:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:791 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.141 secs / 0.126 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:794 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.141 secs / 0.126 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.50s.
```
