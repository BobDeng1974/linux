
# close the console print
echo "1 1 1 1" > /proc/sys/kernel/printk

# print specifed line of specified file
echo "file drivers/mmc/core/core.c +p" >  /sys/kernel/debug/dynamic_debug/co
ntrol
