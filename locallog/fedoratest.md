```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
21 12 2023 12:12:49.313:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
21 12 2023 12:12:49.314:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
21 12 2023 12:12:49.318:INFO [launcher]: Starting browser Firefox
21 12 2023 12:12:51.126:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket UeAWeTOfGel_AKtrAAAB with id 61847386
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
21 12 2023 12:12:51.913:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 61847386
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.129 secs)
21 12 2023 12:12:52.042:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 129 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:741 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.152 secs)
21 12 2023 12:12:52.110:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 23 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:808 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.172 secs)
21 12 2023 12:12:52.138:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 20 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:836 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.229 secs / 0.172 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:844 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.229 secs / 0.172 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 15.15s.
```
