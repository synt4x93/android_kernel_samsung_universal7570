# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_DTS_EXYNOS7570_J4LTE_MEA_OPEN_00) += exynos7570-j4lte_mea_open_00.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_J4LTE_MEA_OPEN_01) += exynos7570-j4lte_mea_open_01.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_J4LTE_MEA_OPEN_02) += exynos7570-j4lte_mea_open_02.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_XCOVER4LTE_EUR_OPEN_00) += exynos7570-xcover4lte_eur_open_00.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_XCOVER4LTE_EUR_OPEN_01) += exynos7570-xcover4lte_eur_open_01.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_XCOVER4LTE_EUR_OPEN_02) += exynos7570-xcover4lte_eur_open_02.dtb
dtb-$(CONFIG_DTS_EXYNOS7570_XCOVER4LTE_EUR_OPEN_04) += exynos7570-xcover4lte_eur_open_04.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
