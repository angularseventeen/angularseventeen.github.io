```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
14 02 2024 09:27:23.197:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
14 02 2024 09:27:23.199:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
14 02 2024 09:27:23.202:INFO [launcher]: Starting browser Firefox
14 02 2024 09:27:24.684:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket -oDMWTz9ft2MKNgDAAAB with id 11057132
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
14 02 2024 09:27:25.142:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 11057132
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.08 secs)
14 02 2024 09:27:25.231:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 80 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:48 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.092 secs)
14 02 2024 09:27:25.244:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:61 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.104 secs)
14 02 2024 09:27:25.274:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:90 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.104 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:95 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.135 secs / 0.104 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.21s.
```
