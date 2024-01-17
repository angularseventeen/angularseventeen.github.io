```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
17 01 2024 16:50:22.765:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
17 01 2024 16:50:22.767:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
17 01 2024 16:50:22.770:INFO [launcher]: Starting browser Firefox
17 01 2024 16:50:24.919:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket xDSnI6cGnO6v68RnAAAB with id 99163785
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
17 01 2024 16:50:25.445:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 99163785
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.091 secs)
17 01 2024 16:50:25.518:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 91 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:766 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.103 secs)
17 01 2024 16:50:25.561:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:809 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.115 secs)
17 01 2024 16:50:25.563:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:811 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.115 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:815 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.12 secs / 0.115 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.19s.
```
