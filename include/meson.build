inc_conf_data = configuration_data()

inc_conf_data.set('PACKAGE_VERSION', '1.9.0')
LS_LT_CURRENT=1
LS_LT_REVISION=9
LS_LT_AGE=0
inc_conf_data.set('LS_LTVERSION', '@LS_LT_CURRENT@:@LS_LT_REVISION@:@LS_LT_AGE@')

configure_file(input : 'sixel.h.in',
               output : 'sixel.h',
               configuration : inc_conf_data)
install_headers('sixel.h')
inc = include_directories('.')
