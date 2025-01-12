use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '5be22f98733c674d532598454ae729253bc53e82',
  'effcee_revision' : 'e63a164aa0a40a04ddca2c18976819668b5a47a8',
  'glslang_revision': 'e43514866f7e0f8265c677039d2fe773c892d44b',
  'googletest_revision': '504ea69cf7e9947be54f808a09b7b08988e84b5f',
  're2_revision': '6dcd83d60f7944926bfd308cc13979fc53dd69ca',
  'spirv_headers_revision': '4183b260f4cccae52a89efdfcdd43c4897989f42',
  'spirv_tools_revision': '360d469b9eac54d6c6e20f609f9ec35e3a5380ad',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
