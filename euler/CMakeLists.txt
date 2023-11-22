cmake_minimum_required (VERSION 3.16)

project(euler C)

set(SRC_LIST
addhe.c
addlist.c
arc.c
bndrlv.c
circle.c
contlv.c
contvv.c
del.c
delhe.c
dellist.c
faceeq.c
init.c
int2ee.c
intrve.c
kef.c
kev.c
larea.c
listsolid.c
lkef.c
lkemr.c
lkev.c
lkfmrh.c
lmef.c
lmekr.c
lmev.c
lmfkrh.c
loopglue.c
mef.c
mev.c
mvfs.c
new.c
revert.c
rsweep2.c
scan.c
scannames.c
solidls.c
svolume.c
torus.c
laringmv.c
contfv.c
merge.c
checkv.c
vector.c
)

add_library( euler STATIC ${SRC_LIST} )
