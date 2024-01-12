```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 01 2024 11:21:19.308:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 01 2024 11:21:19.310:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 01 2024 11:21:19.313:INFO [launcher]: Starting browser Firefox
12 01 2024 11:21:21.133:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket bq4-JdJO9MdK0OQ4AAAB with id 91577414
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 01 2024 11:21:21.660:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 91577414
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.078 secs)
12 01 2024 11:21:21.745:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 78 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:452 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.093 secs)
12 01 2024 11:21:21.751:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:457 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.105 secs)
12 01 2024 11:21:21.792:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:498 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.105 secs)
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


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.133 secs / 0.105 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.65s.
```
