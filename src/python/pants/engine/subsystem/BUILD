# Copyright 2016 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_library(
  name='native',
  sources=['native.py'],
  dependencies=[
    '3rdparty/python:cffi',
    '3rdparty/python:setuptools',
    'src/python/pants/binaries:binary_util',
    'src/python/pants/subsystem:subsystem',
    'src/python/pants/engine:storage',
  ],
  resource_targets=[
    ':native_engine_version'
  ]
)

resources(
  name='native_engine_version',
  sources=['native_engine_version']
)
