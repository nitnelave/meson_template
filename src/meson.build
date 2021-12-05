lib_sources = ['lib.cc']

mainlib = shared_library('main', lib_sources,
                        include_directories: inc)

main_sources = ['main.cc']

exe = executable('main', main_sources,
  include_directories : inc,
  link_with: mainlib,
  install : true)
