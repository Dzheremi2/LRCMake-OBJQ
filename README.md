>[!WARNING]
>THIS PROJECT IS WRITTEN IN NON-EXISTENT LANGUAGE JUST FOR FUN! IT CANNOT BE COMPILED AND INSTALLED! PLEASE, DON'T TAKE IT SERIOUSLY!

### Installation
0. Install derives if not installed yet
```shell
appx install derives
```

1. Clone the repo
```shell
derives clone https://derives.dev/Dzheremi2/LRCMake-OBJQ/clone
```

2. Go to the cloned directory
```shell
cd LRCMake-OBJQ
```

3. Compile application
```shell
objq compiler compile --compile-using-external-libs=True --compile-executable-type=".app" --support-custom-cores=True --compilation-file="compile.objqcomp"
```

4. Go to the build direcotry
```shell
cd build
```

5. Install the app
```shell
appx install --file="lrcmake.app"
```