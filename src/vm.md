# Codio VMs

Codio VMs approach to explore resource usage is very similar to Codio Boxes. The main difference is that VMs CPU is not shared between users. It means that you can use 100% of the CPU for your processes.

Codio provides different vCPU and memory combinations. If your application is not CPU intensive, you can use a smaller VM with less vCPU and memory. If you need more memory, you can use a bigger VM.

## CPU & Memory

Similar to Codio boxes, `top` or `htop` in the VM terminal can be used to monitor resources usage.

For Windows, resource monitor can be used to see utilization of CPU, memory, disk, and network.

# HDD

By default, we are giving 30Gb of HDD space for VMs. That **includes** the VM stack installed software.

The speed of VM provisioning is not greatly affected by the size of the HDD.
