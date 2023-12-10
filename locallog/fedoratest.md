```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
10 12 2023 06:37:22.274:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
10 12 2023 06:37:22.275:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
10 12 2023 06:37:22.278:INFO [launcher]: Starting browser Firefox
10 12 2023 06:37:23.496:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket EKvyFPPxl79Mw96lAAAB with id 41602793
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
10 12 2023 06:37:23.910:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 41602793
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
10 12 2023 06:37:23.997:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:735 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.106 secs)
10 12 2023 06:37:24.030:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:769 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.117 secs)
10 12 2023 06:37:24.036:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:775 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.131 secs / 0.117 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:781 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.131 secs / 0.117 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 13.11s.
```
