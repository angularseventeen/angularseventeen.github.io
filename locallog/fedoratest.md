```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
08 11 2023 16:48:25.385:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
08 11 2023 16:48:25.387:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
08 11 2023 16:48:25.391:INFO [launcher]: Starting browser Firefox
08 11 2023 16:48:26.730:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket NjNjf9RdA4y2dx9UAAAB with id 65731711
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
08 11 2023 16:48:27.152:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 65731711
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.061 secs)
08 11 2023 16:48:27.223:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 61 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:859 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.075 secs)
08 11 2023 16:48:27.234:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:870 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.084 secs)
08 11 2023 16:48:27.240:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:875 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.093 secs / 0.084 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:882 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.093 secs / 0.084 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.22s.
```
