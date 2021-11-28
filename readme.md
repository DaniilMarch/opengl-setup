Steps
1. Get glfw https://github.com/glfw/glfw
2. Build glfw:
```
#in glfw dir
mkdir build
cd build
cmake ..
cmake --build .
make
sudo make install
```
3. get glad https://glad.dav1d.de/
4. unpack `include` to `/usr/include`
`sudo cp -R include/* /usr/include`
5. get `glad.c` to project src