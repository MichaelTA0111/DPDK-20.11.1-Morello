# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2017 Intel Corporation

if is_windows
	subdir_done()
endif

drivers = ['bcmfs', 'null', 'scheduler', 'virtio']

std_deps = ['cryptodev'] # cryptodev pulls in all other needed deps
config_flag_fmt = 'RTE_LIBRTE_PMD_@0@'
