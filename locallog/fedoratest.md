```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
29 12 2023 09:28:09.091:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
29 12 2023 09:28:09.093:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
29 12 2023 09:28:09.096:INFO [launcher]: Starting browser Firefox
29 12 2023 09:28:10.914:INFO [Firefox 121.0 (Linux x86_64)]: Connected on socket da1sNnp8kaVSxRrYAAAB with id 25045832
Firefox 121.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
29 12 2023 09:28:11.435:INFO [Firefox 121.0 (Linux x86_64)]: Starting tests 25045832
[1A[2KFirefox 121.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
29 12 2023 09:28:11.534:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should create the app]: Success: 89 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:458 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 121.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.107 secs)
29 12 2023 09:28:11.569:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should render title]: Success: 18 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:493 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.118 secs)
29 12 2023 09:28:11.571:INFO [Firefox 121.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:494 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.118 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 121.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:500 min/sec/ms


Firefox 121.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.138 secs / 0.118 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.10s.
```
