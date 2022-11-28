### ForAllSecure Hackathon Training

#### CMake Exercise

# Clone & Run Locally (build already done in this repo)

1. clone example and go to directory

```bash
git clone https://github.com/<Your GithuhUsername>mayhem-cmake-example
cd mayhem-cmake-example/
```

2. create build directory and go to build directory (we do '..' for this command because we want to reference the cmake file in our previous directory)

```bash
cmake ..
```

3. (on macOS)

```bash
brew update
brew install cmake
cmake ..
```

4. run make

```bash
make
```

5. when build is finished, run the executable

```bash
./fuzz me
```

6. output should be the following:

```bash
usage: ./fuzzme PAYLOAD
```
