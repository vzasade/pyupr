
This is the repo for upr stream testcases. See below for information on how to
run the testsuite.

Run all tests:

./pyupr

Logging can be changed by specifying 'verbose' option:

(None) - Error logging
 -v    - Warning Logging
 -vv   - Info Logging
 -vvv  - Debug Logging

Test suites can be specified with the 'suite' option

(None)   - Run all tests
 -s all  - Run all tests
 -s upr  - Run all upr related tests
 -s mcd  - Run all memcached related tests
