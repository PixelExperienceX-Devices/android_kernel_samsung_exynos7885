# SPDX-License-Identifier: GPL-2.0
# Galaxy A7 (2018)
dtb-y += exynos/exynos7885-a7y18lte_eur_open_00.dtb
dtb-y += exynos/exynos7885-a7y18lte_eur_open_01.dtb
dtb-y += exynos/exynos7885-a7y18lte_eur_open_03.dtb

# Galaxy A8+
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_00.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_01.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_02.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_03.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_04.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_05.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_06.dtb
dtb-y += exynos/exynos7885-jackpot2lte_eur_open_07.dtb

# Galaxy A8 CAN
dtb-y += exynos/exynos7885-jackpotlte_can_open_00.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_01.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_02.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_03.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_04.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_05.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_06.dtb
dtb-y += exynos/exynos7885-jackpotlte_can_open_07.dtb

# Galaxy A8
dtb-y += exynos/exynos7885-jackpotlte_eur_open_00.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_01.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_02.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_03.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_04.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_05.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_06.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_07.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
