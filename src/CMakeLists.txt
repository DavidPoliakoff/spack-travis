add_executable(printer printer.cpp)
add_test(printer_test printer 2)
set_tests_properties(printer_test PROPERTIES PASS_REGULAR_EXPRESSION "2")
