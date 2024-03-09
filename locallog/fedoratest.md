```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
09 03 2024 09:45:53.333:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
09 03 2024 09:45:53.335:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
09 03 2024 09:45:53.338:INFO [launcher]: Starting browser Firefox
09 03 2024 09:45:54.624:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket XlegYSWzpXqkUFjlAAAB with id 55336386
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
09 03 2024 09:45:54.993:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 55336386
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.066 secs)
09 03 2024 09:45:55.045:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 66 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:1:727 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.079 secs)
09 03 2024 09:45:55.064:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 13 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:1:746 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.09 secs)
09 03 2024 09:45:55.070:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:1:752 min/sec/ms[22m[39m
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.085 secs / 0.09 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m
   * should create the app : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:1:763 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.085 secs / 0.09 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.27s.
```
