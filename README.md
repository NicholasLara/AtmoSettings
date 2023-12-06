# AtmoSettings
system_settings.inf editor for Atmosphère CFW

AtmoSettings is a Homebrew app that allows the user to directly modify their system_settings.inf file stored at sdmc:/switch/atmosphere/config/system_settings.inf .
For the app to function correctly, the user must first move the system_settings.ini from Atmosphere/config_templates/system_settings.ini to sdmc:/switch/atmosphere/config/system_settings.inf, and remove the semicolons at the start of every line in the template.


The app has 6 settings, each binded to a different setting in system_setting.ini:


cheats_enabled_by_default (dmnt_cheats_enabled_by_default = u8!0x1)

USB3.0_enabled (usb30_force_enabled = u8!0x0)

dns_mitm_enabled (enable_dns_mitm = u8!0x1)

error_report_uploads_enabled (upload_enabled = u8!0x0)

sd_card_logging_enabled (enable_sd_card_logging = u8!0x1)

automatic_report_cleanup_disabled (disable_automatic_report_cleanup = u8!0x0)


Built using libnx library in C.
