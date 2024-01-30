```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
30 01 2024 09:08:50.093:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
30 01 2024 09:08:50.096:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
30 01 2024 09:08:50.100:INFO [launcher]: Starting browser Firefox
30 01 2024 09:08:51.668:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket AJwn90XM1DxXElzcAAAB with id 32912682
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
30 01 2024 09:08:52.141:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 32912682
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.091 secs)
30 01 2024 09:08:52.219:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 91 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:168 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
30 01 2024 09:08:52.241:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:190 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
30 01 2024 09:08:52.251:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:200 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.114 secs)
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
Elapsed Time: 0:2:206 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.11s.
```
