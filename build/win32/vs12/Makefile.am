include $(top_srcdir)/Makefile.decl

EXTRA_DIST +=	\
	README.txt	\
	gtk+.sln	\
	gtk-prebuild.vcxproj	\
	gdk-win32.vcxproj	\
	gdk-win32.vcxproj.filters	\
	gdk.vcxproj	\
	gdk.vcxproj.filters	\
	gtk.vcxproj	\
	gtk.vcxproj.filters	\
	gtk-encode-symbolic-svg.vcxproj	\
	gtk-encode-symbolic-svg.vcxproj.filters	\
	gtk3-demo.vcxproj	\
	gtk3-demo.vcxproj.filters	\
	gtk3-demo-application.vcxproj	\
	gtk3-demo-application.vcxproj.filters	\
	gtk-inspector.vcxproj	\
	gtk-inspector.vcxproj.filters	\
	gailutil.vcxproj	\
	gailutil.vcxproj.filters	\
	install.vcxproj	\
	broadwayd.vcxproj	\
	broadwayd.vcxproj.filters	\
	gdk-broadway.vcxproj	\
	gdk-broadway.vcxproj.filters	\
	gtk-build-defines.props	\
	gtk-copy-gdk-broadway.props	\
	gtk-gen-srcs.props	\
	gtk-ignore-broadway.props	\
	gtk-install.props	\
	gtk-version-paths.props

DISTCLEANFILES = $(EXTRA_DIST)

MSVC_SLN = gtk+

MSVC_VER = 12

MSVC_VER_LONG = 2013

include $(top_srcdir)/build/Makefile-newvs.am

-include $(top_srcdir)/git.mk
