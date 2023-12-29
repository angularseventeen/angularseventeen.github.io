```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 12 2023 07:29:04.794:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 12 2023 07:29:04.796:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 12 2023 07:29:04.799:INFO [launcher]: Starting browser Firefox
29 12 2023 07:29:06.604:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket 8nUd53Wih4d_FK7jAAAB with id 27783866
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 12 2023 07:29:07.128:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 27783866
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.097 secs)
29 12 2023 07:29:07.216:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 97 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:434 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.111 secs)
29 12 2023 07:29:07.239:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:458 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.132 secs)
29 12 2023 07:29:07.290:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 21 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:508 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.165 secs / 0.132 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:514 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.165 secs / 0.132 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.06s.
```
