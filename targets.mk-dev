define GLUON_TARGETS :=
ramips-mt7621
x86-64
endef

ifneq ($(BROKEN),0)
define GLUON_TARGETS +=
bcm27xx-bcm2710
bcm27xx-bcm2711
mvebu-cortexa9
endef
endif

GLUON_TARGETS := $(GLUON_TARGETS:\n= )
