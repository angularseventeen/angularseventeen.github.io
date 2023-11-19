```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
19 11 2023 11:03:44.142:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
19 11 2023 11:03:44.143:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
19 11 2023 11:03:44.146:INFO [launcher]: Starting browser Firefox
19 11 2023 11:03:45.399:INFO [Firefox 119.0 (Linux x86_64)]: Connected on socket 24q1JlwAYawj8cBkAAAB with id 46231047
Firefox 119.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
19 11 2023 11:03:45.731:INFO [Firefox 119.0 (Linux x86_64)]: Starting tests 46231047
[1A[2KFirefox 119.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.061 secs)
19 11 2023 11:03:45.789:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 61 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:657 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.071 secs)
19 11 2023 11:03:45.816:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should create the app]: Success: 10 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:684 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.08 secs)
19 11 2023 11:03:45.821:INFO [Firefox 119.0 (Linux x86_64) | AppComponent | should render title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:689 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.094 secs / 0.08 secs)
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
Elapsed Time: 0:1:695 min/sec/ms


Firefox 119.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.094 secs / 0.08 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 5.93s.
```
