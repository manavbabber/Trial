icon_sizes = ['32']

foreach i : icon_sizes
    install_data(
        join_paths('icons',i, 'mana.svg'),
        install_dir: join_paths(get_option('datadir'), 'icons', 'hicolor', i + 'x' + i, 'apps')
    )
endforeach

