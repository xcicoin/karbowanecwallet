**1. Dependencies**

First install all dependencies to build https://github.com/xcicoin/xcicoin
You should be able to build xcicoin from source before continue.
Next, install Qt5. https://wiki.qt.io/Main
Next, clone repositories and build.
You can do it with the following commands if you run use Ubuntu:


**2. Build**

```
git clone https://github.com/xcicoin/xciwallet.git
cd xciwallet
git clone https://github.com/xcicoin/xcicoin cryptonote
mkdir build
cd build
cmake ..
make

```
