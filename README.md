# some_function_bash
add cron job at /etc/crontab: 
@reboot root echo 80 > /sys/class/power_supply/BAT0/charge_control_end_threshold
@reboot root chown khanh /sys/class/backlight/intel_backlight/brightness
@reboot root echo 1 > /proc/sys/kernel/sysrq
