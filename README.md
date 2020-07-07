# Slambook2

## Sophus 

```
git clone https://github.com/strasdat/Sophus.git
cd Sophus
mkdir build
cd build
cmake ..
make -j
```

## Pangolin

```
git clone https://github.com/stevenlovegrove/Pangolin.git
cd Pangolin
mkdir build
cd build
cmake ..
cmake --build .
```


如果出现和anaconda的冲突，就先移走anaconda，然后重新编译

## Ch4
编译的时候需要指定C++11:
```
add_compile_options(-std=c++11)
```