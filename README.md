# autoaspm - Unraid plugin

autoaspm is a plugin that monitors the network traffic speed to automatically enable/disable PCIe ASPM

This plugin has been specifically developed for users with Realtek network adapters. Their drivers suffer from weird ASPM behavior and sometimes don't get the full speed when they are set to `powersave`. For this, this plugin can be useful when you want to achieve the lowest possible power consumption and still want to enjoy fast network speeds.