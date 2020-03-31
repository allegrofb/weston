
ICE_COMMON_SRCS = ['mstring.cc','udir.cc','upath.cc','yapp.cc','yxapp.cc','ytimer.cc',
	'ywindow.cc','ypaint.cc','ypopup.cc','misc.cc','ycursor.cc','ysocket.cc','ypaths.cc',
	'ylocale.cc','yarray.cc','ycollections.cc','ypipereader.cc','yxembed.cc','yconfig.cc',
	'yprefs.cc','yfont.cc','ypixmap.cc','ytime.cc',
	#'yimage_gdk.cc',
	'yximage.cc','ycolor.cc','ytooltip.cc']

t_name = 'keyneswmbg'
t_srcs = ['icewmbg.cc', 'ref.cc'] + ICE_COMMON_SRCS
t_deps = [dep_wayland_client, dep_libshared, dep_lib_cairo_shared, dep_xkbcommon]

executable(
	t_name, t_srcs,
	include_directories: include_directories('..', '../shared'),
	dependencies: t_deps,
	install: true
)
