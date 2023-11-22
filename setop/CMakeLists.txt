cmake_minimum_required (VERSION 3.16)

project(setop C)

set(SRC_LIST
contfp.c
dosetopgen.c
dovertexonf.c
inside.c
sectors.c
separ.c
setop.c
setopcl.c
setopgen.c
setopgetnbr.c
sinsert.c
srecledges.c
sreclsectors.c
updmaxnames.c
vtxfaccl.c
vtxvtxcl.c
setopconnect.c
ssortedges.c
setopfinish.c
)

add_library( setop STATIC ${SRC_LIST} )
