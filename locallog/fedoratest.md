```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 11 2023 12:36:31.201:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 11 2023 12:36:31.202:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 11 2023 12:36:31.205:INFO [launcher]: Starting browser Firefox
19 11 2023 12:36:32.440:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket LjMDm8cixxQptLyQAAAB with id 4534143
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 11 2023 12:36:32.752:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 4534143
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.062 secs)
19 11 2023 12:36:32.813:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 62 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:623 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.071 secs)
19 11 2023 12:36:32.829:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:638 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.08 secs)
19 11 2023 12:36:32.839:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:648 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.08 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:651 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.08 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.00s.
```
