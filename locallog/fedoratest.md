```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 01 2024 13:16:05.000:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 01 2024 13:16:05.003:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 01 2024 13:16:05.006:INFO [launcher]: Starting browser Firefox
19 01 2024 13:16:07.169:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket m8ywJHYT7GnbXS2mAAAB with id 40974248
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 01 2024 13:16:07.747:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 40974248
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
19 01 2024 13:16:07.824:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:850 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.099 secs)
19 01 2024 13:16:07.837:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:862 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
19 01 2024 13:16:07.846:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:871 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.103 secs / 0.114 secs)
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
Elapsed Time: 0:2:878 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.103 secs / 0.114 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.95s.
```
