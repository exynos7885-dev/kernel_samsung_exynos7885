# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_EXYNOS_DECON_LCD_S6D7AA0_XCOVER4S) += exynos/dtbo/exynos7885.dtb
dtbo-$(CONFIG_EXYNOS_DECON_LCD_S6D7AA0_XCOVER4S) += exynos/dtbo/exynos7884-xcover4s_eur_open_00.dtbo
dtbo-$(CONFIG_EXYNOS_DECON_LCD_S6D7AA0_XCOVER4S) += exynos/dtbo/exynos7884-xcover4s_eur_open_02.dtbo

dtb-$(CONFIG_EXYNOS_DECON_LCD_S6E3FA7_A7Y18) += exynos/exynos7885-a7y18lte_eur_open_00.dtb
dtb-$(CONFIG_EXYNOS_DECON_LCD_S6E3FA7_A7Y18) += exynos/exynos7885-a7y18lte_eur_open_01.dtb
dtb-$(CONFIG_EXYNOS_DECON_LCD_S6E3FA7_A7Y18) += exynos/exynos7885-a7y18lte_eur_open_03.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
