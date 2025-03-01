# TODO compile executable that will be run  
add_executable(core 
	many_object_in_stack_example.cpp
)  	# create executable using specified source code files

target_include_directories(core 
	PRIVATE ${EIGEN3_INCLUDE_DIR}
)

target_link_libraries(core
	core_library
)
