
ALL: lib

CFLAGS   = ${PNETCDF_INCLUDE}
FFLAGS   =
SOURCEC  = pbvec.c pdvec.c pvec2.c vmpicr.c commonmpvec.c
SOURCEF  =
SOURCEH  = pvecimpl.h
LIBBASE  = libpetscvec
MANSEC   = Vec
DIRS     = mpicusp mpiviennacl
LOCDIR   = src/vec/vec/impls/mpi/

include ${PETSC_DIR}/lib/petsc/conf/variables
include ${PETSC_DIR}/lib/petsc/conf/rules
include ${PETSC_DIR}/lib/petsc/conf/test
