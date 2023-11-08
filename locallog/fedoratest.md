```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
08 11 2023 16:08:21.987:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 11 2023 16:08:21.989:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 11 2023 16:08:21.993:INFO [launcher]: Starting browser Firefox
08 11 2023 16:08:23.281:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket nGix7EBIYCdQWTuBAAAB with id 33100439
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 11 2023 16:08:23.682:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 33100439
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.075 secs)
08 11 2023 16:08:23.744:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'angularseventeengithubio' title]: Success: 75 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:774 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'angularseventeengithubio' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
08 11 2023 16:08:23.754:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:784 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.095 secs)
08 11 2023 16:08:23.764:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:794 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.083 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'angularseventeengithubio' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:798 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.083 secs / 0.095 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 13.21s.
```
