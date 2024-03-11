```bash
yarn run v1.22.22
$ ng test --karma-config karma.conf.js
11 03 2024 08:58:01.705:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
11 03 2024 08:58:01.707:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
11 03 2024 08:58:01.710:INFO [launcher]: Starting browser Firefox
11 03 2024 08:58:03.191:INFO [Firefox 123.0 (Linux x86_64)]: Connected on socket CedcoHa3wIMRt14wAAAB with id 47194470
Firefox 123.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
11 03 2024 08:58:03.657:INFO [Firefox 123.0 (Linux x86_64)]: Starting tests 47194470
[1A[2KFirefox 123.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.055 secs)
11 03 2024 08:58:03.710:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should render title]: Success: 55 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:19 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.064 secs)
11 03 2024 08:58:03.721:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 9 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:30 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.072 secs)
11 03 2024 08:58:03.731:INFO [Firefox 123.0 (Linux x86_64) | AppComponent | should create the app]: Success: 8 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:41 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.077 secs / 0.072 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 123.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:45 min/sec/ms


Firefox 123.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.077 secs / 0.072 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 6.42s.
```
