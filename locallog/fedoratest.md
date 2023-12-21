```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
21 12 2023 16:29:10.816:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
21 12 2023 16:29:10.818:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
21 12 2023 16:29:10.821:INFO [launcher]: Starting browser Firefox
21 12 2023 16:29:12.838:INFO [Firefox 120.0 (Linux x86_64)]: Connected on socket 1M5XTX7rsB6qioJzAAAB with id 67537817
Firefox 120.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
21 12 2023 16:29:13.595:INFO [Firefox 120.0 (Linux x86_64)]: Starting tests 67537817
[1A[2KFirefox 120.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.122 secs)
21 12 2023 16:29:13.726:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should create the app]: Success: 122 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:920 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 120.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.149 secs)
21 12 2023 16:29:13.792:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should render title]: Success: 27 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:987 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.168 secs)
21 12 2023 16:29:13.800:INFO [Firefox 120.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 19 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:994 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.207 secs / 0.168 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 120.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:3:1 min/sec/ms


Firefox 120.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.207 secs / 0.168 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 17.64s.
```
