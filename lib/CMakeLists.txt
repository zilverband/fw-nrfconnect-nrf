#
# Copyright (c) 2018 Nordic Semiconductor
#
# SPDX-License-Identifier: LicenseRef-BSD-5-Clause-Nordic
#

add_subdirectory_ifdef(CONFIG_BSD_LIBRARY bsdlib)
add_subdirectory_ifdef(CONFIG_DK_LIBRARY dk_buttons_and_leds)
add_subdirectory_ifdef(CONFIG_AT_HOST_LIBRARY at_host)
