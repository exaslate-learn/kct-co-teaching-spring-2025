```sh
cp -r 0_orig 0
cp -r constant/polyMesh_orig constant/polyMesh
decomposePar
mpirun -np 6 sonicFoam -parallel
```