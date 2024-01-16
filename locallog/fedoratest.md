```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
16 01 2024 09:31:17.950:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 01 2024 09:31:17.952:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 01 2024 09:31:17.955:INFO [launcher]: Starting browser Firefox
16 01 2024 09:31:19.871:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket TkLvfCLJ7438zZ24AAAB with id 97741862
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 01 2024 09:31:21.372:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 97741862
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
16 01 2024 09:31:21.389:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 103 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:3:451 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
16 01 2024 09:31:21.391:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:3:453 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.133 secs)
16 01 2024 09:31:21.393:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:3:454 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.023 secs / 0.133 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:460 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.023 secs / 0.133 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 12.08s.
```
