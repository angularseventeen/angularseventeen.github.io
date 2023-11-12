```bash
yarn run v1.22.19
$ ng test --karma-config karma.conf.js
12 11 2023 09:16:25.577:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
12 11 2023 09:16:25.578:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
12 11 2023 09:16:25.581:INFO [launcher]: Starting browser Firefox
12 11 2023 09:16:26.745:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket qee_PTE8g9RtiPeVAAAB with id 23608656
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
12 11 2023 09:16:27.018:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 23608656
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.055 secs)
12 11 2023 09:16:27.074:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 55 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:508 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.063 secs)
12 11 2023 09:16:27.080:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:515 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.075 secs)
12 11 2023 09:16:27.096:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 12 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:530 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.08 secs / 0.075 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 119.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:535 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.08 secs / 0.075 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.85s.
```
