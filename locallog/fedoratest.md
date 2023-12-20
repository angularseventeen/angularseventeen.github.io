```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 12 2023 21:33:56.231:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 12 2023 21:33:56.233:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 12 2023 21:33:56.236:INFO [launcher]: Starting browser Firefox
19 12 2023 21:33:58.049:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket rXUu3Hl3r4hfR5CQAAAB with id 94535521
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 12 2023 21:33:58.547:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 94535521
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.085 secs)
19 12 2023 21:33:58.643:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 85 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:424 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.101 secs)
19 12 2023 21:33:58.724:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 16 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:506 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.112 secs)
19 12 2023 21:33:58.733:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:514 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.188 secs / 0.112 secs)
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
Elapsed Time: 0:2:518 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.188 secs / 0.112 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 8.03s.
```
