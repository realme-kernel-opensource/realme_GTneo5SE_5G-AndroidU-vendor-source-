# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.

#ifdef OPLUS_FEATURE_ZRAM_OPT
obj-$(CONFIG_OPLUS_FEATURE_ZRAM_OPT) 	+= zram_opt/
#endif /* CONFIG_OPLUS_FEATURE_ZRAM_OPT */

#ifdef OPLUS_FEATURE_VIRTUAL_RESERVE_MEMORY
obj-$(CONFIG_VIRTUAL_RESERVE_MEMORY)	+= gloom/
#endif /* OPLUS_FEATURE_VIRTUAL_RESERVE_MEMORY */

#ifdef OPLUS_FEATURE_PROCESS_RECLAIM
obj-$(CONFIG_PROCESS_RECLAIM_ENHANCE)	+= process_reclaim/
#endif /* OPLUS_FEATURE_PROCESS_RECLAIM */

#ifdef OPLUS_FEATURE_MEMLEAK_DETECT
obj-$(CONFIG_DUMP_TASKS_MEM)	+= dump_tasks_mem/
obj-$(CONFIG_MEMLEAK_DETECT)	+= memleak_detect/
#endif /* OPLUS_FEATURE_MEMLEAK_DETECT */


obj-$(CONFIG_MAPPED_PROTECT) += memload_opt/mapped_protect/
obj-$(CONFIG_PCPPAGES_OPT) += async_reclaim_opt/pcppages_opt/
