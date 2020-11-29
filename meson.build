# project name and programming language
project('com.github.manavbabber.Trial', 'vala', 'c')

i18n = import('i18n')

add_project_arguments(
    '-DGETTEXT_PACKAGE="@0@"'.format(meson.project_name()),
    language: 'c'
)
<<<<<<< HEAD

=======
>>>>>>> 3f773955296d08323072500d9fd8ba76cf337cfa
# Create a new executable, list the files we want to compile, list the dependencies we need, and install
executable(
    meson.project_name(),
    'src/Application.vala',
    dependencies: [
        dependency('gtk+-3.0'),
    ],
    install: true
)

#Install our .desktop file so the Applications Menu will see it
install_data(
    join_paths('data', 'hello-again.desktop.in'),
    install_dir: join_paths(get_option('datadir'), 'applications')
)

#Install our .appdata.xml file so AppCenter will see it
install_data(
    join_paths('data','hello-again.appdata.xml.in'),
    install_dir: join_paths(get_option('datadir'), 'metainfo')
)

subdir('data')
subdir('po')
<<<<<<< HEAD
=======

>>>>>>> 3f773955296d08323072500d9fd8ba76cf337cfa
