# gtest
This repo just show the basic usage of gtest in your project.

# How to build

```bash
cd gtest && make build
cd build
cmake ..
make
```

# How to run

## run the samples

```bash
cd build/samples
./hello_test
```

## list all of the test cases in this hello_test.

```bash
cd build/samples
./hello_test --gtest_list_tests

# Show more usage.
./hello_test --help
```

