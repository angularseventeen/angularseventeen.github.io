```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
27 11 2023 12:16:13.388:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
27 11 2023 12:16:13.390:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
27 11 2023 12:16:13.393:INFO [launcher]: Starting browser Firefox
27 11 2023 12:16:15.031:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket S4EZpkbX5ZYLNV_WAAAB with id 86316859
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
27 11 2023 12:16:15.356:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 86316859
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.052 secs)
27 11 2023 12:16:15.409:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 52 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:32 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.059 secs)
27 11 2023 12:16:15.421:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 7 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:43 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.065 secs)
27 11 2023 12:16:15.429:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 6 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:51 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.074 secs / 0.065 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:55 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.074 secs / 0.065 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.11s.
```
