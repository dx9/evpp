include_defs('//BUCKAROO_DEPS')

cxx_library(
    name = 'evpp',
    header_namespace = 'evpp',
    srcs = glob([
        ('evpp/*.cc'),
        ('evpp/**/*.cc')
    ]),
    exported_headers = subdir_glob([
        ('evpp', '*.h'),
        ('evpp', '**/*.h')
    ]),
    deps = BUCKAROO_DEPS,
    visibility = ['PUBLIC']
)

cxx_library(
    name = 'evnsq',
    header_namespace = 'evnsq',
    compiler_flags = ['-DRAPIDJSON_HAS_STDSTRING=1'],
    srcs = glob([
        ('apps/evnsq/*.cc')
    ]),
    exported_headers = subdir_glob([
        ('apps/evnsq', '*.h')
    ]),
    deps = BUCKAROO_DEPS,
    visibility = ['PUBLIC']
)
