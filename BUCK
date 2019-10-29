load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'catch2',
  header_namespace = '',
  header_only = True,
  exported_headers = subdir_glob([
    ('single_include', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
