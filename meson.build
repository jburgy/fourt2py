project('testpkg', 'c',
    version : '0.1',
    default_options : [
        'optimization=3',
        'warning_level=1',
        'fortran_std=legacy',
        'python.install_env=venv',
    ]
)

py = import('python').find_installation(pure : true)

subdir('src')