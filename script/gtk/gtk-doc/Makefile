GARNAME = gtk-doc
GARVERSION = 1.27
CATEGORIES = gtk
MASTER_SITES = http://ftp.gnome.org/pub/GNOME/sources/gtk-doc/1.27/
DISTFILES = $(DISTNAME).tar.xz
LICENSE = GPL3

DESCRIPTION =
define BLURB
endef

DEPENDS = lang/c

INSTALL_SCRIPTS = gtk-doc.m4
#INSTALL_SCRIPTS = custom

include ../../gar.mk

install-gtk-doc.m4:
#install:
	@mkdir -p $(DESTDIR)$(datadir)/aclocal
	@rm -f $(DESTDIR)$(datadir)/aclocal/gtk-doc.m4
	@cp $(WORKSRC)/gtk-doc.m4 $(DESTDIR)$(datadir)/aclocal/gtk-doc.m4
	@$(MAKECOOKIE)
