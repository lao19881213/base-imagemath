add_executable(tprimarybeam tprimarybeam.cc)
target_link_libraries(tprimarybeam 
	askap_imagemath
	${CPPUNIT_LIBRARY}
)
add_test(
	NAME tprimarybeam
	COMMAND tprimarybeam
	)
