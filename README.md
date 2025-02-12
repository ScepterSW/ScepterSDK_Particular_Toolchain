## Scepter Software Develop Kit

### Supported Devices

- NYX Camera

  - NYX650/660 (NYX650_R_20240325_B02  and later )

- Vzense Camera
    - DS86/87 (DS86_R_20230321  and later )
    - DS77C (DS77_S_20220530_B16  and later )
    - DS77 (DS77_S_20220530_B16  and later) 

### Supported Platform

- Arm-linux-gnueabihf 

### Folder description
- **Arm-linux-gnueabihf-v5.4.0_v24.12.2**

    Ubuntu16.04 arm32 SDK package with standard compiler arm-linux-gnueabihf(v5.4.0)
- **Arm-linux-gnueabihf-v4.9.2_v24.12.2** 

   Ubuntu16.04 arm32 SDK package with standard compiler arm-linux-gnueabihf(v4.9.2)


### Summary Of The Guidelines

- Choose the right version for different device types

- Refer to samples and documents for functional development

### Resources

- Download links: https://github.com/ScepterSW , https://gitee.com/ScepterSW
- Develop wiki: https://wiki.vzense.com/#/

### Others

Copy the OpenCV library which in **Samples**  to the system directory, then run the XXXSample which in **PrecompiledSamples**.

```
cp /Samples/OpenCV/Thirdparty/opencv-3.4.1/lib/* /lib/arm-linux-gnueabihf/
```

