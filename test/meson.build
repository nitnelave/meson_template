gtest_proj = subproject('gtest')
gtest_dep = gtest_proj.get_variable('gtest_dep')
gmock_dep = gtest_proj.get_variable('gmock_dep')

testexe = executable('testexe', 'test.cc',
                     include_directories : inc,
                     dependencies: gtest_dep,
                     link_with: mainlib)
test('main test', testexe)

