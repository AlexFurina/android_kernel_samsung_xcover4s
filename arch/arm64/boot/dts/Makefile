# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/dtbo/exynos7885.dtb

dtb-$(CONFIG_MACH_EXYNOS7885_XCOVER4S_OPEN) := \
	exynos7884-xcover4s_eur_open_00.dtbo \
        exynos7884-xcover4s_eur_open_02.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
