cxx_library(
  name = 'http-parser',
  header_namespace = '',
  exported_headers = [
    'http_parser.h'
  ],
  srcs = [
    'http_parser.c',
  ],
  licenses = [
    'LICENSE-MIT',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'bench',
  srcs = [
    'bench.c',
  ],
  deps = [
    ':http-parser',
  ],
)

cxx_binary(
  name = 'test',
  srcs = [
    'test.c',
  ],
  deps = [
    ':http-parser',
  ],
)
