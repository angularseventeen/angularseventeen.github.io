```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
24 02 2024 06:20:42.441:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
24 02 2024 06:20:42.442:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
24 02 2024 06:20:42.445:INFO [launcher]: Starting browser Firefox
24 02 2024 06:20:43.743:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket AGK_Mp4sHEncYwh9AAAB with id 8936397
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
24 02 2024 06:20:44.135:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 8936397
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.059 secs)
24 02 2024 06:20:44.193:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 59 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:768 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.069 secs)
24 02 2024 06:20:44.215:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:789 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.08 secs)
24 02 2024 06:20:44.217:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:791 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.091 secs / 0.08 secs)
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
Elapsed Time: 0:1:801 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.091 secs / 0.08 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.58s.
```
