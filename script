# To enable battery conservation mode 
# setcharging 1

# To disable it
# setcharging 0

# Default is enabled
function setcharging()
{
        echo ${1:-1}  | sudo tee /sys/bus/platform/drivers/ideapad_acpi/VPC2004\:00/conservation_mode
}
