# OSI Model Troubleshooting
In this module we are going to get some knowledge of troubleshooting methods and the software and hardware tools to use to diagnose problems. This module covers the most common issues that you will find when troubleshooting a network.

# Physical Layer problems
Issues on a network often present as performance problems. Performance problems mean that here is a difference between the expected behavior and the observer behavior. Failures and suboptimal conditions at the physical layer not only incovenience user but can impact the productivity of the entire company.

Due upper layers of the OSI model depend on the physical layer to function, an administrator must have the ability to effectively isolate and correct them.

## Common Physical layer symptoms
* **Performance lower than baseline**
  * Requires previous baselines for comparision.
  * Most common reasons include overloaded or underpowered servers, traffic congestion on a link and chronic frame loss.
* **Loss of connectivity**
  * Could be due to a failed or disconnected cable.
  * Can be verified using a simple ping test.
* **Network bottlenecks or congestion**
  * If a device or interface fails, routing protocols may redirect traffic to other routes that are not capable to carry the extra capacity.
  * This resuls on congestion in parts of the network.
* **High CPU utilization rates**
  * Are a symptom that a device is operating at or exceeding its design limits.
  * Can cause a device to shut down or fail if it is not solved quickly.
* **Console error messages**
  * Error messages reported on the device console could indicate a physical layer problem.
  * Console messages should be logged to a central syslog server.

## Common Physical layer causes
* **Power-related**
  * Most fundamental reason for network failure.
  * If other nearby units have also powered down, suspect a power failure at the main power supply.
* **Cabling faults**
  * Many problems can be corrected by simply reseating cables that have become partially disconnected.
  * Look for damaged cables, improper cable types and connectors.
  * Suspect cables should be tested with a known functioning cable.
* **Attenuation**
  * If a cable length exceeds the design limit for the media.
  * If is severe, the receiving device cannot always succesfully distinguish one bit in the data stream from another bit.
* **Interface configuration errors**
  * Misconfigurations such as incorrect clock rate, incorrect clock source and interface not being turned on.
  * This causes a loss of connectivty with attached network segments.

[Physical Layer problems and causes](imgs/layer_1.png)

# Data Link Layer Troubleshooting
## Common symproms
* **No functionality or connectivity at L2 or above**
  * some problems can stop the exchange of frames stopping the conectivity
  * some others just cause the network performancen degradation
 * **Network is operating below baselaaine perfomance levels**
   *  


# Transport Layer
## ACLs
* **Symptoms**
* Connectivity Issues
* Access Issuess
* **Causes**
* ACL configurations
* NAT configurations
