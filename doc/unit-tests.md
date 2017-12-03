Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disaled.

After configuring, they can be run with `make check`.

To run the sucrd tests manually, launch `src/test/test_sucr`.

To add more sucrd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the sucr-qt tests manually, launch `src/qt/test/test_sucr-qt`

To add more sucr-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
