# Registries
- [example](https://github.com/sunzhenkai/vcpkg-base)

# Usage
Full example is [here](https://github.com/sunzhenkai/vcpkg-base-example).

# Insall Vcpkg
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/sunzhenkai/vcpkg-base/main/scripts/install_vcpkg_pure.sh)"
```

# Dependencies
- make
- cmake
- automake
- autoconf
- ninja

# overlay port
```shell
vcpkg install gperftools --overlay-ports=$(pwd)/ports/
```

