# Copyright (c) 2024 Intel Corporation.
# SPDX-License-Identifier: Apache-2.0

sof_llext_build("aux1_fir"
	SOURCES fir_common.c
		../fir_generic.c
		../fir_hifi2ep.c
		../fir_hifi3.c
		../fir_hifi5.c
	LIB openmodules
)
