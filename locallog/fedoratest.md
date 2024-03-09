```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 03 2024 16:01:50.944:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 03 2024 16:01:50.946:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 03 2024 16:01:50.950:INFO [launcher]: Starting browser Firefox
09 03 2024 16:01:52.556:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket 3whroWiyK4ROT8TcAAAB with id 88235144
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 03 2024 16:01:53.046:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 88235144
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
09 03 2024 16:01:53.143:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 98 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:217 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.112 secs)
09 03 2024 16:01:53.153:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:228 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.126 secs)
09 03 2024 16:01:53.167:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:241 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.139 secs / 0.126 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:262 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.139 secs / 0.126 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.92s.
```
