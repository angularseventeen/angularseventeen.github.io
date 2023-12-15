```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
15 12 2023 12:25:46.152:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
15 12 2023 12:25:46.154:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
15 12 2023 12:25:46.158:INFO [launcher]: Starting browser Firefox
15 12 2023 12:25:47.397:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket GG0m3twrbKvYkYDIAAAB with id 45906976
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
15 12 2023 12:25:47.791:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 45906976
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.063 secs)
15 12 2023 12:25:47.870:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 63 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:742 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.072 secs)
15 12 2023 12:25:47.872:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:743 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.084 secs)
15 12 2023 12:25:47.878:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:750 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.084 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:753 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.088 secs / 0.084 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.17s.
```
