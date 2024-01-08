```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
08 01 2024 17:46:05.896:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 01 2024 17:46:05.898:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 01 2024 17:46:05.902:INFO [launcher]: Starting browser Firefox
08 01 2024 17:46:07.946:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket 8gggaGkVs0_cOSi7AAAB with id 15770605
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 01 2024 17:46:08.587:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 15770605
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.127 secs)
08 01 2024 17:46:08.696:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 127 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:833 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.151 secs)
08 01 2024 17:46:08.714:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 24 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:851 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.168 secs)
08 01 2024 17:46:08.732:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:869 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.153 secs / 0.168 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:881 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.153 secs / 0.168 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.37s.
```
