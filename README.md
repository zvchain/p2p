P2P Core is ZVChain network transfer layer implementation, network transfer protocol use  KCP, a open source RUDP implementation,it provide NAT Traversal ability,let nodes under NAT can be connecting with other.

## Requirements

macOS X

    clang 10.0.1

Linux

    GCC 8.0
 
Windows

    Mingw-w64 
    GCC 8.0
  
  
## Build

MacOS X

```shell
cd platform/darwin
make 
```
Linux

```shell
cd platform/linux
make 
```

Window

```shell
cd platform/windows
make 
```



## License

```
Copyright (C) 2018 ZVChain

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
