# Copyright (c) Meta Platforms, Inc. and affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

add_fb_python_library(pywatchman
  SOURCES
    __init__.py
    capabilities.py
    encoding.py
    load.py
    pybser.py
    windows.py
  NAMESPACE pywatchman
)
