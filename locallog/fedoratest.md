```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 01 2024 09:47:44.135:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 01 2024 09:47:44.137:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 01 2024 09:47:44.140:INFO [launcher]: Starting browser Firefox
12 01 2024 09:47:45.954:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket OjAk4fruzNePLwbfAAAB with id 94303558
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 01 2024 09:47:46.496:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 94303558
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.099 secs)
12 01 2024 09:47:46.619:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 99 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:497 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.11 secs)
12 01 2024 09:47:46.621:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:499 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.122 secs)
12 01 2024 09:47:46.623:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:502 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.129 secs / 0.122 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:507 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.129 secs / 0.122 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.92s.
```
