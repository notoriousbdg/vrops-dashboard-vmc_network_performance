
# Network Performance for VMware Cloud on AWS Dashboard for vRealize Operations Cloud and vRealize Operations
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to view performance of NSX Edges in VMware Cloud on AWS.  Monitor throughput, packets per second, and dropped packets for NSX Edges.  Use the heatmaps to find top talkers and troubleshoot.  Optionally, you can add coloring to the packets per second metric chart based on the model of the host the edges are running on.  NSX Edges running on i3 can support up to 800,000 packets per second and NSX Edges running on i3en hosts can support up to 1,600,000 packets per second.

## Screenshots
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vmc_network_performance/main/images/Dashboard.png)

## Installation
1. Import the dashboard at `Visualize` / `Dashboards` / `Manage` / `...` / `Import`
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-vmc_network_performance/main/images/Dashboard_Import.png)
1. Click `Browse...` then select the file named [Dashboards.zip](https://github.com/notoriousbdg/vrops-dashboard-vmc_network_performance/raw/main/Dashboards.zip)
1. The included dashboards are listed in the [Dashboards section](#Dashboards)

## Dashboards
| Dashboard Name | Dashboard Path |
|--|--|
| Network Performance for VMware Cloud on AWS | Shared Dashboards (GBrandon)/Troubleshooting |

## Support

This dashboard requires vRealize Operations Cloud or vRealize Operations 8.2 (or newer)

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-vmc_network_performance/issues) for feedback.

## Changelog
2022-08-03
* Initial release
