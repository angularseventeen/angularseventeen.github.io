```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
25 11 2023 10:36:01.791:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
25 11 2023 10:36:01.792:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
25 11 2023 10:36:01.795:INFO [launcher]: Starting browser Firefox
25 11 2023 10:36:03.259:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket jXDzOX0Z-7TYkEovAAAB with id 23288626
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
25 11 2023 10:36:03.631:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 23288626
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.058 secs)
25 11 2023 10:36:03.685:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 58 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:917 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.067 secs)
25 11 2023 10:36:03.701:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:933 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.079 secs)
25 11 2023 10:36:03.703:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:935 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.077 secs / 0.079 secs)
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
Elapsed Time: 0:1:942 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.077 secs / 0.079 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.21s.
```
