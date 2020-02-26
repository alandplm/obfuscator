# Fork README

Current Fork version: [LLVM-4.0](https://github.com/alandplm/obfuscator/tree/llvm-4.0)

## Instalation

### Ubuntu 19.10

sudo apt install ocaml ocaml-libs ninja-build cmake doxygen sphinx-doc sphinx-common git libevent-dev libncurses-dev pkg-config gcc-7 g++-7

git clone -b llvm-4.0 https://github.com/alandplm/obfuscator.git
mkdir build
cd build
cmake -G "Unix Makefiles" -DCMAKE_C_COMPILER="gcc-7" -DCMAKE_CXX_COMPILER="g++-7" -DCMAKE_BUILD_TYPE=Release -DLLVM_INCLUDE_TESTS=OFF ../obfuscator
make -j7


# Upstream README
Please have a look at the [wiki](https://github.com/obfuscator-llvm/obfuscator/wiki)!

Current version: [LLVM-4.0](https://github.com/obfuscator-llvm/obfuscator/tree/llvm-4.0)

You can cite Obfuscator-LLVM using the following Bibtex entry:

```
@INPROCEEDINGS{ieeespro2015-JunodRWM,
  author={Pascal Junod and Julien Rinaldini and Johan Wehrli and Julie Michielin},
  booktitle={Proceedings of the {IEEE/ACM} 1st International Workshop on Software Protection, {SPRO'15}, Firenze, Italy, May 19th, 2015},
  editor = {Brecht Wyseur},
  publisher = {IEEE},
  title={Obfuscator-{LLVM} -- Software Protection for the Masses},
  year={2015},
  pages={3--9},
  doi={10.1109/SPRO.2015.10},
}
```
