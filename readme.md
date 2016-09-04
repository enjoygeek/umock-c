This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# testrunnerswitcher

umock_c is a C mocking library.

## Setup

- Clone umock_c by:
```
git clone --recursive https://github.com/Azure/umock-c.git
```
- Create a cmake folder under the root of umock-c
- Switch to the cmake folder and run
   cmake ..
- Build the code for your platform (msbuild for Windows, make for Linux, etc.)

## Dependencies

umock_c uses ctest as test runner (https://github.com/Azure/azure-ctest.git). ctest is a C test runner that can be run on many platforms as it does not make use of compiler/platform specific code and thus it is easily portable.
umock_c uses cmake (https://cmake.org/) to generate build files.
umock_c uses testrunnerswitcher to allow switching between ctest and CppUnitTest for Windows. 

## Documentation

See the doc folder 