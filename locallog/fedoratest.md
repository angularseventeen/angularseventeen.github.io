```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
12 02 2024 14:08:48.663:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 02 2024 14:08:48.665:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 02 2024 14:08:48.668:INFO [launcher]: Starting browser Firefox
12 02 2024 14:08:50.464:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket YcKzXjqS3hHeiCgBAAAB with id 86721986
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 02 2024 14:08:50.979:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 86721986
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.108 secs)
12 02 2024 14:08:51.100:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 108 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:451 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.12 secs)
12 02 2024 14:08:51.103:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:454 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.134 secs)
12 02 2024 14:08:51.111:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:461 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.159 secs / 0.134 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:492 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.159 secs / 0.134 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.17s.
```
