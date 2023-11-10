```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
09 11 2023 19:25:56.437:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 11 2023 19:25:56.438:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 11 2023 19:25:56.441:INFO [launcher]: Starting browser Firefox
09 11 2023 19:25:57.637:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket KOOYJyr8PgCdglVWAAAB with id 46425927
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 11 2023 19:25:57.958:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 46425927
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
09 11 2023 19:25:58.038:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 77 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:611 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.091 secs)
09 11 2023 19:25:58.054:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:627 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
09 11 2023 19:25:58.065:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:638 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.109 secs / 0.101 secs)
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
Elapsed Time: 0:1:642 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.109 secs / 0.101 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.89s.
```
