```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
02 02 2024 06:09:35.809:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
02 02 2024 06:09:35.811:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
02 02 2024 06:09:35.814:INFO [launcher]: Starting browser Firefox
02 02 2024 06:09:37.950:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket Em_1XnwkhIDX51AoAAAB with id 93636029
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
02 02 2024 06:09:38.506:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 93636029
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.089 secs)
02 02 2024 06:09:38.616:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 89 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:820 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.104 secs)
02 02 2024 06:09:38.626:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:829 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.118 secs)
02 02 2024 06:09:38.634:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 14 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:837 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.13 secs / 0.118 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should render title : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:844 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.13 secs / 0.118 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.98s.
```
