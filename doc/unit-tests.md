Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the localtraded tests manually, launch src/test/test_localtrade .

To add more localtraded tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the localtrade-qt tests manually, launch src/qt/test/localtrade-qt_test

To add more localtrade-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
