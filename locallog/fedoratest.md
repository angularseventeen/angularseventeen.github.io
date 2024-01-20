```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
20 01 2024 09:50:19.785:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
20 01 2024 09:50:19.787:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
20 01 2024 09:50:19.789:INFO [launcher]: Starting browser Firefox
20 01 2024 09:50:21.567:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket uwFOjAJov0NKtUyKAAAB with id 80517790
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
20 01 2024 09:50:22.145:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 80517790
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
20 01 2024 09:50:22.221:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 95 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:451 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.112 secs)
20 01 2024 09:50:22.266:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:496 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.124 secs)
20 01 2024 09:50:22.269:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:498 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.126 secs / 0.124 secs)
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
Elapsed Time: 0:2:503 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.126 secs / 0.124 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.63s.
```
