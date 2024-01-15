```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
15 01 2024 10:37:59.692:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
15 01 2024 10:37:59.694:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
15 01 2024 10:37:59.698:INFO [launcher]: Starting browser Firefox
15 01 2024 10:38:01.545:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket qMzU05XB6obBwA1NAAAB with id 43730049
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
15 01 2024 10:38:02.121:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 43730049
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
15 01 2024 10:38:02.266:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 101 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:588 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
15 01 2024 10:38:02.276:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:597 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.128 secs)
15 01 2024 10:38:02.277:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:599 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.157 secs / 0.128 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:603 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.157 secs / 0.128 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.44s.
```
