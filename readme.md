# Microsoft Azure IoT SDK for Python

This repository contains the following:

* **Azure IoT Hub Device SDK**: to connect client devices to Azure IoT Hub

To find SDKs in other languages for Azure IoT, please refer to the [azure-iot-sdks][azure-iot-sdks] repository.

## Developing applications for Azure IoT

Visit [Azure IoT Dev Center][iot-dev-center] to learn more about developing applications for Azure IoT.

## How to use the Azure IoT SDKs for Python
Devices and data sources in an IoT solution can range from a simple network-connected sensor to a powerful, standalone computing device. Devices may have limited processing capability, memory, communication bandwidth, and communication protocol support. The IoT device SDKs enable you to implement client applications for a wide variety of devices.

* **Using PyPI package on Windows (coming soon for Linux)**: the simplest way to use the Azure IoT SDK for Python to develop device apps on Windows is to leverage the PyPI package which you can install following these [instructions][PyPI-install-instructions]
* **Building the library and working with the SDK code**: follow [these instructions][devbox-setup].


## Samples

Whithin the repository, you can find various types of simple samples that can help you get started.
And if you are looking for end to end samples that show how to do simple analytics and processing of the data generated by your device using Azure services such as Stream Analytics, Big Data, Machine Learning and others, check out our [E2E samples gallery](http://aka.ms/azureiotsamples).
To run the samples, you can follow [these instructions][run-samples]

* [Simple Sample](device/samples/iothub_client_sample.py): shows how to connect to IoT Hub and send and receive messages using the AMQP, MQTT or HTTP protocol.
* [Class Sample using AMQP](device/samples/iothub_client_sample_class.py): shows how to connect to IoT Hub with a HubManager class to send and receive messages using the AMQP protocol.


## Contribution, feedback and issues

If you encounter any bugs, have suggestions for new features or if you would like to become an active contributor to this project please follow the instructions provided in the [contribution guidelines](CONTRIBUTING.md).

## Support

If you are having issues using one of the packages or using the Azure IoT Hub service that go beyond simple bug fixes or help requests that would be dealt within the [issues section](https://github.com/Azure/azure-iot-sdks/issues) of this project, the Microsoft Customer Support team will try and help out on a best effort basis.
To engage Microsoft support, you can create a support ticket directly from the [Azure portal](https://ms.portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade).
Escalated support requests for Azure IoT Hub SDKs development questions will only be available Monday thru Friday during normal coverage hours of 6 a.m. to 6 p.m. PST.
Here is what you can expect Microsoft Support to be able to help with:
* **Client SDKs issues**: If you are trying to compile and run the libraries on a supported platform, the Support team will be able to assist with troubleshooting or questions related to compiler issues and communications to and from the IoT Hub.  They will also try to assist with questions related to porting to an unsupported platform, but will be limited in how much assistance can be provided.  The team will be limited with trouble-shooting the hardware device itself or drivers and or specific properties on that device. 
* **IoT Hub / Connectivity Issues**: Communication from the device client to the Azure IoT Hub service and communication from the Azure IoT Hub service to the client.  Or any other issues specifically related to the Azure IoT Hub.
* **Portal Issues**: Issues related to the portal, that includes access, security, dashboard, devices, Alarms, Usage, Settings and Actions.
* **REST/API Issues**: Using the IoT Hub REST/APIs that are documented in the [documentation]( https://msdn.microsoft.com/library/mt548492.aspx).

## Read more

* [Azure IoT Hub documentation][iot-hub-documentation]
* [Python run sample][run-samples] describes how to run a simple Python sample for Azure IoT Hub.
* [FAQ](doc/faq.md) contains frequently asked questions about the SDKs and libraries.

---
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

[iot-dev-center]: http://azure.com/iotdev
[iot-hub-documentation]: https://docs.microsoft.com/en-us/azure/iot-hub/
[azure-iot-sdks]: http://github.com/azure/azure-iot-sdks
[PyPI-install-instructions]: doc/python-devbox-setup.md#windows-wheels
[devbox-setup]: doc/python-devbox-setup.md
[run-samples]: doc/python-run-sample.md