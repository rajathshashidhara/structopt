project(
    'structopt',
    'cpp',
    version : '0.1.4',
    license : 'MIT'
)

includes = include_directories(['single_include'])

install_headers([
    'single_include/structopt/structopt.hpp',
], subdir: 'structopt')

structopt_dep = declare_dependency(
    include_directories: includes
)
