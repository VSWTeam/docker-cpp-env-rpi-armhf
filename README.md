# docker-cpp-env-rpi-armhf

C++ ARMv7 開發環境，包含下面軟體：

- CMake
- Conan
- SSH server
- GDB server

## 使用方法

### Conan based projects

```
docker run --rm -it -v $(pwd):/project vswteam/cpp-env-rpi-armhf:latest "mkdir -p build && cd build && conan install .. && conan build .."
```
