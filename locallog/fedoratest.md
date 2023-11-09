```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
09 11 2023 05:04:57.936:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 11 2023 05:04:57.938:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 11 2023 05:04:57.940:INFO [launcher]: Starting browser Firefox
09 11 2023 05:04:59.129:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket 5kf7rF5NioZih3FFAAAB with id 21362888
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 11 2023 05:04:59.464:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 21362888
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.057 secs)
09 11 2023 05:04:59.522:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 57 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:597 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.065 secs)
09 11 2023 05:04:59.539:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:613 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.076 secs)
09 11 2023 05:04:59.545:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:619 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.09 secs / 0.076 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:630 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.09 secs / 0.076 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.98s.
```
