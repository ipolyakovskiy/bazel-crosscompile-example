package(default_visibility = ['//visibility:public'])

filegroup(
    name = "all",
    srcs = glob(["**/*"])
)

filegroup(
    name = 'gcc',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-gcc',
    ],
)

filegroup(
    name = 'ar',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-ar',
    ],
)

filegroup(
    name = 'ld',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-ld',
    ],
)

filegroup(
    name = 'nm',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-nm',
    ],
)

filegroup(
    name = 'objcopy',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-objcopy',
    ],
)

filegroup(
    name = 'objdump',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-objdump',
    ],
)

filegroup(
    name = 'strip',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-strip',
    ],
)

filegroup(
    name = 'as',
    srcs = [
        'bin/x86_64-unknown-linux-gnu-as',
    ],
)

filegroup(
    name = 'compiler_components',
    srcs = [
        ':gcc',
        ':ar',
        ':ld',
        ':nm',
        ':objcopy',
        ':objdump',
        ':strip',
        ':as',
    ],
)

filegroup(
    name = 'compiler_pieces',
    srcs = glob([
        'x86_64-unknown-linux-gnu/**',
        'lib/**',
    ]),
)

