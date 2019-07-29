# On Ubuntu, setup gtest environment

# (as root)
# apt-get install libgtest
# apt-get install cmake
# cd /usr/src/gtest
# cmake CMakeLists.txt
# make
# cp *.a /usr/lib

# (as user)
$ mkdir gtest-example
$ cd gtest-example
$ git clone https://github.com/ichibrosan/GTest
$ cd GTest
$ cmake CMakeLists.txt
$ make
$ ./runTests

See [http://www.eriksmistad.no/getting-started-with-google-test-on-ubuntu/](http://www.eriksmistad.no/getting-started-with-google-test-on-ubuntu/) for a guide to getting started with google test on Ubuntu
