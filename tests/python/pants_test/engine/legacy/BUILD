# Copyright 2016 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  name = 'address_mapper',
  sources = ['test_address_mapper.py'],
  dependencies = [
    'src/python/pants/engine/legacy:structs',
  ]
)

python_tests(
  name = 'build_ignore_integration',
  sources = [ 'test_build_ignore_integration.py' ],
  dependencies = [
    'tests/python/pants_test:int-test',
  ],
  tags = {'integration'},
)

python_tests(
  name = 'bundle_integration',
  sources = ['test_bundle_integration.py'],
  dependencies = [
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'}
)

python_tests(
  name = 'dependees_integration',
  sources = ['test_dependees_integration.py'],
  dependencies = [
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
)

python_tests(
  name = 'dependencies_integration',
  sources = ['test_dependencies_integration.py'],
  dependencies = [
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
  timeout = 90,
)

python_tests(
  name = 'filemap_integration',
  sources = ['test_filemap_integration.py'],
  dependencies = [
    'src/python/pants/base:project_tree',
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
  timeout = 180,
)

python_tests(
  name = 'graph',
  sources = ['test_graph.py'],
  dependencies = [
    '3rdparty/python:mock',
    'src/python/pants/bin',
    'src/python/pants/build_graph',
  ]
)

python_tests(
  name = 'structs',
  sources = ['test_structs.py'],
  dependencies = [
    'src/python/pants/engine/legacy:structs',
  ]
)

python_tests(
  name = 'list_integration',
  sources = ['test_list_integration.py'],
  dependencies = [
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
  timeout = 180,
)

python_tests(
  name = 'pants_engine_integration',
  sources = ['test_pants_engine_integration.py'],
  dependencies = [
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'}
)

python_tests(
  name = 'changed_integration',
  sources = ['test_changed_integration.py'],
  dependencies = [
    'tests/python/pants_test:base_test',
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
  timeout = 300,
)