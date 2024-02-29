```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 02 2024 18:58:49.400:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 02 2024 18:58:49.402:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 02 2024 18:58:49.404:INFO [launcher]: Starting browser Firefox
29 02 2024 18:58:50.999:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket tMzKsecJ5mIa28SrAAAB with id 3507753
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 02 2024 18:58:51.622:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 3507753
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.114 secs)
29 02 2024 18:58:51.732:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 114 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:342 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.132 secs)
29 02 2024 18:58:51.764:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:374 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.151 secs)
29 02 2024 18:58:51.775:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:385 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.156 secs / 0.151 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:391 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.156 secs / 0.151 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 16.21s.
```
