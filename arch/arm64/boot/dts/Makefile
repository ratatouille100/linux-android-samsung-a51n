# SPDX-License-Identifier: GPL-2.0
dtbo-y += samsung/exynos9611-a51_eur_open_07.dtbo
dtbo-y += samsung/exynos9611-a51_eur_open_03.dtbo
dtbo-y += samsung/exynos9611-a51_eur_open_01.dtbo
dtbo-y += samsung/exynos9611-a51_eur_open_00.dtbo
dtb-y += exynos/exynos9610.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
