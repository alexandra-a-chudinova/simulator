# Container Virtualization Simulator
 Simulation of physical servers hosting containerized CAD applications

The virtual environment simulates a distributed computing cluster consisting of physical servers, on which numerous CAD applications are deployed within containers.

The characteristics of each virtual server include:
* **CPU Load:** Real-time processor utilization and core performance tracking.
* **Memory Usage:** Active RAM consumption, allocation rates, and available headroom.
* **Storage Capacity:** Total disk space, read/write throughput, and volume utilization.
* **Network Bandwidth:** Inbound and outbound traffic rates, packet loss, and transfer speeds.
* **Active Containers:** The total count and operational status of containers currently running on the server.

The parameters for each container include:
* **Computational Resource Requirements:** CPU and processing thresholds needed for execution.
* **Memory Consumption:** Current and peak RAM utilization by the container process.
* **Execution Status:** Real-time operational state (e.g., running, stopped, restarting, failed).
* **Service Priority:** Importance tier or scheduling weight governing resource preemption and allocation.
* **Migration History:** Log of past transfers, live migrations, or host shifts for auditing and tracking.

The system continuously recalculates these parameters following every action taken by a student, allowing for the real-time observation of the consequences of engineering decisions.

RU version: https://blazorrepl.telerik.com/repl/embed/GgEiPsPU10yzdKxa36?editor=false&result=true&errorList=false
EN version: https://blazorrepl.telerik.com/repl/embed/wAvklWwY12zG3TeR21?editor=true&result=true&errorList=true
