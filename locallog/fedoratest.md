```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
21 02 2024 12:22:31.067:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
21 02 2024 12:22:31.069:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
21 02 2024 12:22:31.073:INFO [launcher]: Starting browser Firefox
21 02 2024 12:22:32.819:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket Cagdm_L2wzaEKAopAAAB with id 58734741
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
21 02 2024 12:22:33.337:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 58734741
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.096 secs)
21 02 2024 12:22:33.441:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 96 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:389 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.109 secs)
21 02 2024 12:22:33.447:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:394 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.122 secs)
21 02 2024 12:22:33.465:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:413 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.132 secs / 0.122 secs)
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
Elapsed Time: 0:2:419 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.132 secs / 0.122 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.80s.
```
