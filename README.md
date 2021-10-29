# OpenCore-HP-Z620

This is not intended to be any sort of landmark, this is a ball of duck tape that works for me. If you do use it, I can't promise anything. I am accepting any pull requests however. Always looking to learn more. If you have any general questions, feel free to leave them on the forum part.

## **Rename the config.plist and fix the SMBIOS information with [macserial](https://github.com/acidanthera/macserial)! This is not optional!**

I'll edit this more in a bit to flesh it out but it comes down to this:

    * I have a first gen boot block Z620, thus limiting my CPU choices.
    * Intended for Big Sur / Monterey.
    * Dual Intel Xeon E5-2643 @ 3.30 with power manangement enabled for both CPUs.
    * AMD Vega 64 video card requiring almost nothing weird.
