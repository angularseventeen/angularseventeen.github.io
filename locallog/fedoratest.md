```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
20 12 2023 18:36:04.070:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
20 12 2023 18:36:04.072:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
20 12 2023 18:36:04.075:INFO [launcher]: Starting browser Firefox
20 12 2023 18:36:05.848:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket gr5wjUDywd4iN1OlAAAB with id 18626642
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
20 12 2023 18:36:06.358:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 18626642
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.093 secs)
20 12 2023 18:36:06.444:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 93 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:387 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
20 12 2023 18:36:06.466:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:408 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.121 secs)
20 12 2023 18:36:06.509:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:452 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.154 secs / 0.121 secs)
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
Elapsed Time: 0:2:456 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.154 secs / 0.121 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.23s.
```
