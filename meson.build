
project('PAV_P2', 'c')

sndfile_dep = dependency('sndfile')
math_dep = meson.get_compiler('c').find_library('m')

executable('vad',
  ['src/main_vad.c', 'src/vad.c', 'src/pav_analysis.c'],
  dependencies: [sndfile_dep, math_dep]
)
