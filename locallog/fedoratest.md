```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
11 02 2024 09:18:45.007:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 02 2024 09:18:45.009:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 02 2024 09:18:45.012:INFO [launcher]: Starting browser Firefox
11 02 2024 09:18:46.865:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket jVoF03MX2W8ZoKj1AAAB with id 64482032
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 02 2024 09:18:47.486:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 64482032
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.084 secs)
11 02 2024 09:18:47.555:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 84 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:573 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
11 02 2024 09:18:47.558:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:576 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
11 02 2024 09:18:47.580:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:598 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.096 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:602 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.096 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.47s.
```
