```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
18 12 2023 00:01:13.695:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
18 12 2023 00:01:13.697:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
18 12 2023 00:01:13.700:INFO [launcher]: Starting browser Firefox
18 12 2023 00:01:14.966:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket 0yno0SqEEV8SPgG3AAAB with id 48251053
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
18 12 2023 00:01:15.316:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 48251053
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.054 secs)
18 12 2023 00:01:15.367:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 54 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:698 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.067 secs)
18 12 2023 00:01:15.380:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:711 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.077 secs)
18 12 2023 00:01:15.393:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:724 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.079 secs / 0.077 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:729 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.079 secs / 0.077 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.76s.
```
