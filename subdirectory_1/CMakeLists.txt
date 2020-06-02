set(sources "sourcefile.cpp")
set(linklibs "lib1")
set(properties " ")
set(targets " ")

# build a shared library, install it and corresponding header files
defBI(sources "SHARED" linklibs targets properties ON)
