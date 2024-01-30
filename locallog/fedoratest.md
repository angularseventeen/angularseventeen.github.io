```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 01 2024 23:16:45.049:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 01 2024 23:16:45.052:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 01 2024 23:16:45.057:INFO [launcher]: Starting browser Firefox
29 01 2024 23:16:46.780:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket r6vSd7zUeSF0MdiwAAAB with id 68605519
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 01 2024 23:16:47.393:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 68605519
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.119 secs)
29 01 2024 23:16:47.499:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 119 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:482 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.144 secs)
29 01 2024 23:16:47.527:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 25 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:511 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.161 secs)
29 01 2024 23:16:47.557:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 17 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:541 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.17 secs / 0.161 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:550 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.17 secs / 0.161 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 9.29s.
```
