Binwalk 2.3.2 Windows portable package

Usage:
  binwalk.exe --help
  binwalk.exe -B firmware.bin
  binwalk.exe -Me firmware.bin
  binwalk.exe -Me -C output firmware.bin

This executable was built with Python 3.11 and PyInstaller. It includes the
Binwalk Python package and its package data. It does not include external
firmware extraction utilities such as sasquatch, jefferson, or ubi_reader.
Some extraction operations therefore require those tools to be installed and
available on PATH, or should be performed in WSL/Docker.

The input firmware is processed locally. Do not run untrusted firmware on a
production machine; use an isolated Windows account, VM, WSL distribution, or
container when appropriate.

Binwalk is distributed under the MIT License. Keep LICENSE and NOTICE.md with
the executable when sharing it.
