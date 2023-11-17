```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
16 11 2023 22:50:47.714:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
16 11 2023 22:50:47.715:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
16 11 2023 22:50:47.718:INFO [launcher]: Starting browser Firefox
16 11 2023 22:50:48.926:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket FCt-by9RSz0cYiNvAAAB with id 19891580
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
16 11 2023 22:50:49.263:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 19891580
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.069 secs)
16 11 2023 22:50:49.331:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 69 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:628 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.081 secs)
16 11 2023 22:50:49.344:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:641 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
16 11 2023 22:50:49.350:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:646 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.095 secs / 0.089 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:656 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.095 secs / 0.089 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.10s.
```
