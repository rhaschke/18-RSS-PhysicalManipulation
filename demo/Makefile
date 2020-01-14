BASE = ../rai

DEPEND = Core Kin Gui Geo KOMO Logic LGP Optim
DEPEND_UBUNTU = gcc-5 g++-5

build: $(DEPEND:%=makeDepend/%) x.exe

initUbuntuPackages: installUbuntuPackages $(DEPEND:%=initUbuntuPackages/%)

include $(BASE)/build/generic.mk
