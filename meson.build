project('lemonbar', 'c', version: '1.3.0')

add_global_arguments('-DVERSION="' + meson.project_version() + '"', language: 'c')

freetype = dependency('freetype2')
x = dependency('x11')
x_xcb = dependency('x11-xcb')
xcb = dependency('xcb')
xcb_randr = dependency('xcb-randr')
xft = dependency('xft')

executable('lemonbar', 'lemonbar.c', dependencies: [freetype, x, x_xcb, xcb, xcb_randr, xft])
