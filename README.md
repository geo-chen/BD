# BD

**Brand**: Brandless

**Product**: Dashcam

**Model**: BD S1

**Wifi**: BD_DVR_*

**Product Links**:
 - https://www.amazon.co.uk/Recorder-DashCam-Parking-Monitor-Driving/dp/B0D2D2Y9RP
 - https://shopee.sg/product/1005164622/23245123858?
 - https://www.desertcart.sc/products/645291124-dash-cam-wifi-car-dvr-hd-1080-p-dash-cam-auto-recorder-video-dash-cam-24-h-parking-monitor-black-box-car-camera-driving-recorder-easy-installation-bd-wifi-car-charger-none
 - https://www.amazon.se/-/en/1005005506852055/dp/B0D7CJKS4S
 - https://shopee.sg/WIFI-Mini-Car-DVR-Dash-Camera-USB-WIFI-Car-Recorder-Vedio-Car-DVR-Camera-Recorder-DashCam-for-IPhone-Android-Phone-i.1005164622.23647743187

## Finding 1: Unauthenticated Access of Livestream and Download of Video Recordings

**Description**: Once connected to the dashcam, an attacker can dump all video recordings via rtsp://$DASHCAM_IP:554/$filename without any further authentication. To obtain a list of video recording file names, the following steps need to be performed via API calls on port 80:

 - register the client
 - start live
 - set work mode
 - fetch file list
   
![image](https://github.com/user-attachments/assets/e05867ca-9a5b-4251-bc3b-ab06938157ed)


**Vulnerability Type**: Incorrect Access Control

**Vendor of Product**: BD DVR

**Affected Product Code Base**: BD DVR

**Affected Component**: Video storage and live feed

**Attack Type**: Remote

**Impact Code execution**: False

**Impact Information Disclosure**: True

**Attack Vectors**: An attacker connected to the dashcam's network can access the live feed and dump all sensitive video recordings.

**Has vendor confirmed or acknowledged the vulnerability?**: No


**Product Images**:

![image](https://github.com/user-attachments/assets/be297e7b-0f09-45d9-b8b2-010e4eb23c4b)

![image](https://github.com/user-attachments/assets/c346147f-6177-4ba5-9716-2e4bb1cedda0)

![image](https://github.com/user-attachments/assets/fb3c6c65-2166-4373-a4c3-99e3b54c142e)

![image](https://github.com/user-attachments/assets/1060600b-791d-408e-b3ed-73a20c383840)

