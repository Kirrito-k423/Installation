./configure --prefix=/home/users/industry/isc2020/iscst11/shaojiemike/Install/OpenMPI-cuda --with-cuda=/usr/local/cuda-9.0 --with-tm=/opt/pbs --enable-mpi-cxx


mpirun
-mca ??
-map-by ppr:32:node -bind-to core