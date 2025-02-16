# RPIPico2FreeRTOSRepoExample
FreeRTOS on the Pico2 using the FreeRTOS Original Repo and RP2350 Configuration

Raspberry Pi has depricated their own [FreeRTOS Kernel fork](https://github.com/raspberrypi/FreeRTOS-Kernel) and we are moving back to the main  [FreeRTOS Kernel repo](https://github.com/FreeRTOS/FreeRTOS-Kernel). That now has RP2350 support as a community support out of the [repo](https://github.com/FreeRTOS/FreeRTOS-Kernel-Community-Supported-Ports).

In this project I demonstrate a Pico 2/RP2350 projects in 1 Core and 2 Core (SMP) modes of FreeRTOS Kernel using the upgade FreeRTOS Kernel and Community support libraries. The version of the kernel I have to use is the current head of the FreeRTOS Kernel repo as support is not in V11.1.0 which is the current release.

The example  works out how may times it can calculate the value of PI to 1,000 decimal places in 1 minute. Output is on stdout over Uart on GPIO 16 and 17.

I explain more about this repo and the current version of FreeRTOS kernel on my [YouTube Channel](https://youtube/com/@drjonea)
