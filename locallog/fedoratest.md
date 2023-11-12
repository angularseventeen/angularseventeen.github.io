```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
12 11 2023 09:44:35.021:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 11 2023 09:44:35.023:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 11 2023 09:44:35.027:INFO [launcher]: Starting browser Firefox
12 11 2023 09:44:36.272:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket LoWt8gqldhf9daJ1AAAB with id 86077472
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 11 2023 09:44:36.577:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 86077472
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.069 secs)
12 11 2023 09:44:36.648:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 69 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:645 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.076 secs)
12 11 2023 09:44:36.661:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 7 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:658 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.085 secs)
12 11 2023 09:44:36.673:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:670 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.098 secs / 0.085 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:675 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.098 secs / 0.085 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.18s.
```
