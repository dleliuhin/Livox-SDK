# Livox SDK Communication Protocol

There are two types of communication between the user and LiDAR unit(s), and the
protocol formats of these two kinds of data are different. The specific functions 
and differences are as follows:

> - **Control Command Data**: Configuration and query of LiDAR parameters and status
information;
> - **Point Cloud Data**: Point cloud coordinate data generated by LiDAR units;
At present, both protocols are encapsulated in the data segment of the UDP
package, and the data format in protocol is stored in little-endian form.

Please refer to the [Livox SDK Communication Protocol](https://github.com/Livox-SDK/Livox-SDK/wiki/Livox-SDK-Communication-Protocol) for further information.
