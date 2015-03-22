# fedora-vtk
.spec and patches for the creation of a VTK rpm package on recent Fedoras. Tested in Fedora 21.

Based on Fedora 17 5.8.0-6 orion's original spec (found on the .src.rpm package at https://kojipkgs.fedoraproject.org//packages/vtk/5.8.0/6.fc17/src/vtk-5.8.0-6.fc17.src.rpm) with the required changes for making it work in the updated environment of recent Fedoras.

## How to use

Deploy the .spec file and patches to your rpmbuild root (use the included stupid `deploy` script) and run rpmbuild.
