# statistic_cheat_sheet

[![Actions Status](https://github.com/HeliosMon/statistic_cheat_sheet/workflows/CI/badge.svg)](https://github.com/HeliosMon/statistic_cheat_sheet)
[![Join the chat at https://gitter.im/LaTeX4Ei/Lobby](https://badges.gitter.im/LaTeX4Ei/Lobby.svg)](https://gitter.im/LaTeX4Ei/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Write beautiful latex cheat sheets with minimal effort.

## Formelsammlung für Latex4ei

**Required custom Package on GitHub:** [LaTeX4Ei](https://github.com/latex4ei/latex4ei-packages)

Public Version: [latex4ei.de](http://latex4ei.de)

## Optional: Build with CMake

Download [UseLaTeX.cmake](https://cmake.org/Wiki/CMakeUserUseLATEX) and move to `/usr/share/cmake-X.X/Modules/.`

##### Steps to build:

```shell
mkdir build
cd build
cmake ..
make
```
## Disclaimer

After changing the repository name or transfering ownership, run the "Update README and LaTeX Build" workflow from the Actions tab and merge the generated pull request.
Make sure the `.tex` file has the same name as the repository in order for it to build correctly!
