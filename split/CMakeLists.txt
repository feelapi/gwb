cmake_minimum_required (VERSION 3.16)

project(split C)

set(SRC_LIST
block.c
classify.c
cleanup.c
dist.c
getnbrhd.c
insertnlledg.c
joincut.c
missing.c
neighbor.c
recledges.c
reclsectors.c
sortedges.c
split.c
splitclassif.c
splitconnect.c
splitfinish.c
splitgen.c
sweep.c
)

add_library( split STATIC ${SRC_LIST} )
