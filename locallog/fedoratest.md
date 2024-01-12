```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 01 2024 10:59:52.310:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 01 2024 10:59:52.312:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 01 2024 10:59:52.315:INFO [launcher]: Starting browser Firefox
12 01 2024 10:59:54.124:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket VozGXo644OyueHSZAAAB with id 76435718
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 01 2024 10:59:54.608:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 76435718
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.086 secs)
12 01 2024 10:59:54.700:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 86 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:404 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.099 secs)
12 01 2024 10:59:54.706:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:409 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.116 secs)
12 01 2024 10:59:54.720:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:423 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:428 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.113 secs / 0.116 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.79s.
```
