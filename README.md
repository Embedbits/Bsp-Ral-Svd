# Svd

SVD files (CMSIS System View Description, the peripheral registers shown by
debuggers) of the STMicroelectronics STM32 device family packs.

This branch holds only this file. The files are on the branches
`Releases/<Family>` (e.g. `Releases/STM32F7`), imported by `Svd_Importer.sh`
of the repository Ral_Importers from the public ST pack server, one commit
`Release <pack> v<version>` per version of a device family pack. The files are
in the root of the branch:

```
<Device>.svd    SVD files of the pack
Devices.csv     assignment of the devices to the SVD files, generated from the pack
                description: Device;Core;File;Pack (Core 0 = the core of the debug
                configuration, the other cores of a multi core device follow)
LICENSE.txt     license of the pack (ST SLA0044)
```
