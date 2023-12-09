```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 12 2023 14:52:29.795:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 12 2023 14:52:29.797:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 12 2023 14:52:29.799:INFO [launcher]: Starting browser Firefox
09 12 2023 14:52:31.191:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket V_2aZ1qWfWJGD6ZZAAAB with id 67782111
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 12 2023 14:52:31.623:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 67782111
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.072 secs)
09 12 2023 14:52:31.705:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 72 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:924 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.083 secs)
09 12 2023 14:52:31.714:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:933 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
09 12 2023 14:52:31.725:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:944 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.109 secs / 0.095 secs)
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
Elapsed Time: 0:1:956 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.109 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 12.92s.
```
