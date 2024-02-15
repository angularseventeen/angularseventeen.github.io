```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
15 02 2024 12:13:50.357:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
15 02 2024 12:13:50.360:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
15 02 2024 12:13:50.363:INFO [launcher]: Starting browser Firefox
15 02 2024 12:13:51.958:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 8VZspOdI0tm5b2NvAAAB with id 6695653
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
15 02 2024 12:13:52.505:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 6695653
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
15 02 2024 12:13:52.608:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 98 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:271 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
15 02 2024 12:13:52.640:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:303 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.125 secs)
15 02 2024 12:13:52.642:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:305 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.14 secs / 0.125 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:311 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.14 secs / 0.125 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.51s.
```
