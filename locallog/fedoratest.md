```bash
yarn run v1.22.21
$ ng test --karma-config karma.conf.js
28 01 2024 22:30:48.476:INFO [karma-server]: Karma v6.4.2 server started at http://localhost:9876/
28 01 2024 22:30:48.478:INFO [launcher]: Launching browsers FirefoxHeadless with concurrency unlimited
28 01 2024 22:30:48.481:INFO [launcher]: Starting browser Firefox
28 01 2024 22:30:50.036:INFO [Firefox 122.0 (Linux x86_64)]: Connected on socket OqA8zNgo355Oyr-QAAAB with id 17965676
Firefox 122.0 (Linux x86_64): Executed 0 of 3[32m SUCCESS[39m (0 secs / 0 secs)
28 01 2024 22:30:50.520:INFO [Firefox 122.0 (Linux x86_64)]: Starting tests 17965676
[1A[2KFirefox 122.0 (Linux x86_64): Executed 1 of 3[32m SUCCESS[39m (0 secs / 0.087 secs)
28 01 2024 22:30:50.626:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should create the app]: Success: 87 ms
[33m[1mTest Num: [22m[39m[33m[1m1[22m[39m
[34m[1mElapsed Time: 0:2:164 min/sec/ms[22m[39m

  AppComponent
    [32m✓ [39mshould create the app
[1A[2KFirefox 122.0 (Linux x86_64): Executed 2 of 3[32m SUCCESS[39m (0 secs / 0.098 secs)
28 01 2024 22:30:50.628:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should have the 'Angular 17' title]: Success: 11 ms
[33m[1mTest Num: [22m[39m[33m[1m2[22m[39m
[34m[1mElapsed Time: 0:2:166 min/sec/ms[22m[39m
    [32m✓ [39mshould have the 'Angular 17' title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0 secs / 0.113 secs)
28 01 2024 22:30:50.665:INFO [Firefox 122.0 (Linux x86_64) | AppComponent | should render title]: Success: 15 ms
[33m[1mTest Num: [22m[39m[33m[1m3[22m[39m
[34m[1mElapsed Time: 0:2:203 min/sec/ms[22m[39m
    [32m✓ [39mshould render title
[1A[2KFirefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.151 secs / 0.113 secs)
[32mTOTAL: 3 SUCCESS[39m
TOTAL: 3 SUCCESS


[4m[1mSuites and tests results:[22m[24m

 - [1mAppComponent[22m :
   * should create the app : [32mok[39m
   * should have the 'Angular 17' title : [32mok[39m
   * should render title : [32mok[39m

[4m[1mBrowser results:[22m[24m

 - [1mFirefox 122.0 (Linux x86_64)[22m: 3 tests
   - [32m3 ok[39m
Elapsed Time: 0:2:211 min/sec/ms


Firefox 122.0 (Linux x86_64): Executed 3 of 3[32m SUCCESS[39m (0.151 secs / 0.113 secs)
[32mTOTAL: 3 SUCCESS[39m

Done in 7.95s.
```
