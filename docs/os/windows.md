# Windows

## Use High Performance power plan
Open Power Options and select the High Performance power plan, or the Ultimate Performance plan if you have Windows 10 Pro for Workstations. For AMD Ryzen users, you may have a Ryzen specific plan. Use that.

## Disable Radeon Chill

Radeon Chill is a power saving feature that introduces a variable framecap. Disable it in the Radeon Settings app:

Go to the Gaming tab, then set global settings or for Team Fortress 2 only if you want to use Chill elsewhere and finally turn Chill off.

## Disable Unnecessary Services
You can use the [W10Privacy tool](https://www.winprivacy.de/deutsch-start/download/) to reduce disk load and other workloads to [improve performance](https://www.phoronix.com/scan.php?page=article&item=windows10-w10priv-wsl).

## Networking optimization

Use [TCP Optimizer](https://www.speedguide.net/downloads.php) to optimize your internet settings.

1. Choose your connection speed with the slider at the top.
2. Choose the optimal setting at the bottom.
3. Click apply changes.

## Driver latency optimization

Badly programmed kernel-mode device drivers might cause latency issues, which lead to problems such as frequent stuttering. The user must sniff out exactly which drivers are causing latency.    
Use [LatencyMon](https://www.resplendence.com/latencymon) and [DPC Latency Checker](https://www.thesycon.de/eng/latency_check.shtml) to analyze latency issues caused by kernel-mode device drivers. If they report issues, try updating your drivers or installing alternate drivers.  
Alternatively, you can [switch your (compatible) drivers to MSI mode](https://forums.guru3d.com/threads/windows-line-based-vs-message-signaled-based-interrupts-msi-tool.378044/) and disable their interrupt limits, although this is for **advanced users only**.
