include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'xpressive',
  header_only = True,
  header_namespace = 'boost/xpressive',
  exported_headers = subdir_glob([
    ('include/boost/xpressive', '**/*.hpp'),
    ('include/boost/xpressive', '**/*.ipp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
