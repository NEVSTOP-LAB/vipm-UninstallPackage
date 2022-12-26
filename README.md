# vipm-UninstallPackage

use [lvcicd:vipm_unInstallPackages](https://github.com/LV-APT/lvCICD/blob/main/docs/Operation-List.md#vipm_buildvipackage--build-vipm-library) to uninstall vipm package.

How to Use it:

```
      - name: vipm-UninstallPackage
        uses: NEVSTOP-LAB/vipm-UninstallPackage@main
        with:
          LabVIEW_Version: 2017
          # Package could be PackageName/PacakgeWithVersion
          Package: ZAlign
```
