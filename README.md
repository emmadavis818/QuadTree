# QuadTree
## How to compile and run Jessica's QuadTree C++ code

This code first requires you to clone Jessica's repository.
In the terminal, this is:
```
git clone https://github.com/jessicajiang15/QuadTree
```

Then, you must download cmake, which I used homebrew to download.
```
brew install cmake
```

If you do not have SFML, and I did not, you will have to download that as well.
```
brew install sfml
```

Compilation:
```
cmake -S . -B build
cd build
make
```

Running:
```
./QuadTree
```
