## miniconf makefiles ## 1.1 ##

TOPDIR := ..

trollock_src = trollock.c auth_pam.c
trollock_cflags += $(X11_CFLAGS)
trollock_libs += $(X11_LIBS) -lpam
trollock_type = bin

include $(TOPDIR)/.config/rules.mk
