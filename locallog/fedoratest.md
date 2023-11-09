```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
09 11 2023 18:38:25.505:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 11 2023 18:38:25.507:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 11 2023 18:38:25.510:INFO [launcher]: Starting browser Firefox
09 11 2023 18:38:27.084:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket COwkOrwlCjwEdawzAAAB with id 46500901
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 11 2023 18:38:27.402:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 46500901
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.049 secs)
09 11 2023 18:38:27.444:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 49 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:949 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.058 secs)
09 11 2023 18:38:27.454:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:958 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.067 secs)
09 11 2023 18:38:27.465:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:969 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.065 secs / 0.067 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:974 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.065 secs / 0.067 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.33s.
```
