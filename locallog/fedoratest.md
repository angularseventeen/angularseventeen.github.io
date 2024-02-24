```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
23 02 2024 21:25:40.370:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
23 02 2024 21:25:40.371:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
23 02 2024 21:25:40.374:INFO [launcher]: Starting browser Firefox
23 02 2024 21:25:41.739:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket 7ap3CVWecM37WgUFAAAB with id 97361427
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
23 02 2024 21:25:42.078:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 97361427
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
23 02 2024 21:25:42.161:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 77 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:802 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
23 02 2024 21:25:42.168:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:808 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
23 02 2024 21:25:42.182:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:823 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.107 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:827 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.107 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.55s.
```
