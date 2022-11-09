# Steps to build

0. Requirements
    - CMake, v3.23+
    - Arm GNU Toolchain, v7+
      - 11.2 is not recommended because of defect "Illegal instruction": https://bugs.linaro.org/show_bug.cgi?id=5825
1. Just run CMake to build
    ```shell
#   auto create build dir
    cmake --toolchain cmake/cortex-m0.cmake -B build
    cmake --build build --target dist
    ```
