# Allied Vision CSI-2 Adapter Board for Nvidia Jetson TX2  Xavier Dev Kit

![nvidia_TX2_Xavier_adapter](/Images/TX2_Xavier_Adapter_Board_1.jpg)
![nvidia_TX2_Xavier_adapter](/Images/TX2_Xavier_Adapter_Board_2.jpg)

This repository contains open hardware design files for an adapter board supporting the Allied Vision Alvium CSI-2 camera pinout to NVidias TX2 and Xavier Development kit CSI-2 connector compatible devices, created by Allied Vision.
The board allows the user to interface with two Alvium MIPI CSI-2 compatible cameras over a Flexible Flat Cable (FFC) connector.

You can also purchase the adapter from [Allied Vision](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10) or from our [distributors](https://www.alliedvision.com/en/avt-locations/avt-distributors/).

## Getting Started

These instructions will get you a copy of the design files to make your own adapter boards for development and testing purposes. 
The board can be produced and assembled using the provided design files. Please take a look at the mechanical layers for more information regarding the PCB stackup recommended for fabrication. 

See our [accessories webpage](https://www.alliedvision.com/en/products/accessories/interface-connections/#!?cameraInterfacefilter=10) and the [Alvium CSI-2 download webpage](https://www.alliedvision.com/en/support/technical-documentation/alvium-csi-2-documentation/) for more information.

### Prerequisites

* A running installation of Altium.
* A PCB producer & PCBA manufacturer or some soldering skills.
* One of the supported embedded boards :
	* Nvidia Jetson TX2 Developer Kit 	
	* Nvidia Jetson AGX Xavier Developer Kit
* One or two supported MIPI CSI-2 FPC cable
	* Allied Vision part numbers #12316, 12317, 12318
* [One or two Allied Vision Alvium CSI-2 camera](https://www.alliedvision.com/en/products/embedded-vision-cameras.html)

### Installing

Open the *CSI2-TX2-XAVIER_Rev01.PrjPcb* project file in your Altium environment.

## Built With

* [Altium Designer 19](https://www.altium.com/altium-designer/de)
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
