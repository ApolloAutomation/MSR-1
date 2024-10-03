# Apollo mmWave CO2 Multisensor Mk1 (MSR-1)

![image](https://github.com/ApolloAutomation/MSR-1/assets/24777085/5f67cf3d-4b61-4867-97e9-057eff124b19)


This sensor offers a wide range of functionality for Home Assistant in a very tiny package.

YAML Files:
- MSR-1.yaml: This file is a minimal config. It doesn't have the bluetooth or OTA components. Use this if you are looking to add BLE proxy or BLE tracking.
- MSR-1_BLE.yaml: This file contains BLE proxy code. We use it as an automated test during our build process. But can be an example for adding BLE proxy to your device.
- MSR-1_Factory.yaml: This is the firmware flashed by us on new devices. It contains the components for ESP improve, allowing easy adoption in Home Assistant. When you load the device in ESPHome addon, it will grab the firmware from MSR-1.yaml which no longer has the improve.

Links: \
Discord (Support/feedback/discussion/future products): [https://dsc.gg/ApolloAutomation] \
Shop: [https://apolloautomation.com](https://apolloautomation.com) \
Wiki: [https://wiki.apolloautomation.com](https://wiki.apolloautomation.com/) \
3D Files: [https://www.printables.com/model/564297-apollo-automation-msr-1-mmwave-co2-multisensor-for](https://www.printables.com/model/564297-apollo-automation-msr-1-mmwave-co2-multisensor-for)
