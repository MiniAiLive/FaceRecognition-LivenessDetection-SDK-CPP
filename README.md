<div align="center">
   <h1> Face Recognition LivenessDetection C++ SDK </h1>
   <img src=https://miniai.live/wp-content/uploads/2024/02/logo_name-1-768x426-1.png alt="MiniAiLive Logo"
   width="300">
</div>

## Welcome to the [MiniAiLive](https://www.miniai.live/)!
This repository contains a C++ application that demonstrates face recognition capabilities using computer vision techniques. The demo utilizes OpenCV and dlib libraries for efficient face detection and recognition with 3D passive face liveness detection (face anti-spoofing).

![demo](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/0859737c-d79e-440f-a400-5aa9097ed818)
### Key Features
 - ### [Face detection](https://demo.miniai.live/): 
    ![face_detect](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/61f02463-09e9-4efa-b904-6f2f453d95d5)

    The SDK utilizes advanced computer vision techniques to detect faces in images or video frames, enabling a wide range of applications. 
 - ### [Face recognition](https://demo.miniai.live/):
 ![face_compare](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/29fcd277-f850-4b83-a5da-dc63fb5f0af7)

    It can recognize known faces by comparing them with a pre-defined database of individuals.
 - ### [Age estimation](https://demo.miniai.live/): 
    It can estimate the age of detected faces.
 - ### [Gender detection](https://demo.miniai.live/):
    It can determine the gender of detected faces.
 - ### [Liveness detection](https://demo.miniai.live/): 
    It can detect whether a face is from a live person or a static image.

### Prerequisites
> - C++ compiler with C++11 support  
> - OpenCV (version 4.6.0)

### Installation
Clone the repository:

```
git clone https://github.com/MiniAI/MiniAIFaceSDK.git
```

### Download

- [Download `vcredist_x64.exe` from Microsoft](https://download.microsoft.com/download/2/E/6/2E61CFA4-993B-4DD4-91DA-3737CD5CD6E3/vcredist_x64.exe)
- [Download `vc_redist.x64.exe` from Microsoft](https://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe)
```java
1. Download the `vcredist_x64.exe`, and `vc_redist.x64.exe` files from the provided link.
2. Double-click the downloaded file to start the installation.
3. Follow the on-screen instructions to complete the installation process.
4. Restart your system if prompted.

For more detailed installation instructions, please refer to the [official Microsoft documentation](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redistributable).

```

### Usage
Run the compiled executable:
```java 
./MiniAIFaceDemo.exe
```
We provide free license to test our SDK according to HWID.
You can get the HWID in our SDK application.
Follow the on-screen instructions to perform face detection and recognition.

![HWID](https://github.com/MiniAiLive/MiniAIFaceSDK/assets/136824647/75d935ff-bf2d-4dd2-ac8f-5b356785f91a)
### Customization
> - Face Database: Replace the sample face database with your own set of known faces. Ensure that you provide clear and properly labeled images for accurate recognition.
> - Recognition Algorithm: Adjust the recognition algorithm parameters or explore other algorithms provided by dlib to optimize the recognition performance.


## Face & IDSDK Online Demo, Resources
<div style="display: flex; justify-content: center; align-items: center;"> 
   <table style="text-align: center;">
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://github.com/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_git-1-300x67.png" style="height: 60px; margin-right: 5px;" title="GITHUB"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://huggingface.co/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_hugging-1-300x67.png" style="height: 60px; margin-right: 5px;" title="HuggingFace"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://demo.miniai.live"><img src="https://miniai.live/wp-content/uploads/2024/10/new_gradio-300x67.png" style="height: 60px; margin-right: 5px;" title="Gradio"/></a></td> 
      </tr> 
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://docs.miniai.live/"><img src="https://miniai.live/wp-content/uploads/2024/10/a-300x70.png" style="height: 60px; margin-right: 5px;" title="Documentation"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://www.youtube.com/@miniailive"><img src="https://miniai.live/wp-content/uploads/2024/10/Untitled-1-300x70.png" style="height: 60px; margin-right: 5px;" title="Youtube"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://play.google.com/store/apps/dev?id=5831076207730531667"><img src="https://miniai.live/wp-content/uploads/2024/10/googleplay-300x62.png" style="height: 60px; margin-right: 5px;" title="Google Play"/></a></td>
      </tr>
   </table>
</div>

## Our Products

### Face Recognition SDK
| No | Project | Features |
|----|---------|-----------|
| 1 | [FaceRecognition-SDK-Docker](https://github.com/MiniAiLive/FaceRecognition-SDK-Docker) | 1:1 & 1:N Face Matching SDK |
| 2 | [FaceRecognition-SDK-Windows](https://github.com/MiniAiLive/FaceRecognition-SDK-Windows) | 1:1 & 1:N Face Matching SDK |
| 3 | [FaceRecognition-SDK-Linux](https://github.com/MiniAiLive/FaceRecognition-SDK-Linux) | 1:1 & 1:N Face Matching SDK |
| 4 | [FaceRecognition-LivenessDetection-SDK-Android](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-SDK-Android) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection SDK |
| 5 | [FaceRecognition-LivenessDetection-SDK-iOS](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-SDK-iOS) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection SDK |
| 6 | [FaceRecognition-LivenessDetection-SDK-CPP](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-SDK-CPP) | 1:1 & 1:N Face Matching, 2D & 3D Face Passive Liveness Detection SDK |
| 7 | [FaceMatching-SDK-Android](https://github.com/MiniAiLive/FaceMatching-SDK-Android) | 1:1 Face Matching SDK |
| 8 | [FaceAttributes-SDK-Android](https://github.com/MiniAiLive/FaceAttributes-SDK-Android) | Face Attributes, Age & Gender Estimation SDK |

### Face Liveness Detection SDK
| No | Project | Features |
|----|---------|-----------|
| 1 | [FaceLivenessDetection-SDK-Docker](https://github.com/MiniAiLive/FaceLivenessDetection-SDK-Docker) | 2D & 3D Face Passive Liveness Detection SDK |
| 2 | [FaceLivenessDetection-SDK-Windows](https://github.com/MiniAiLive/FaceLivenessDetection-SDK-Windows) | 2D & 3D Face Passive Liveness Detection SDK |
| 3 | [FaceLivenessDetection-SDK-Linux](https://github.com/MiniAiLive/FaceLivenessDetection-SDK-Linux) | 2D & 3D Face Passive Liveness Detection SDK |
| 4 | [FaceLivenessDetection-SDK-Android](https://github.com/MiniAiLive/FaceLivenessDetection-SDK-Android) | 2D & 3D Face Passive Liveness Detection SDK |
| 5 | [FaceLivenessDetection-SDK-iOS](https://github.com/MiniAiLive/FaceLivenessDetection-SDK-iOS) | 2D & 3D Face Passive Liveness Detection SDK |

### ID Document Recognition SDK
| No | Project | Features |
|----|---------|-----------|
| 1 | [ID-DocumentRecognition-SDK-Docker](https://github.com/MiniAiLive/ID-DocumentRecognition-SDK-Docker) | ID Document, Passport, Driver License, Credit Card, MRZ Recognition SDK |
| 2 | [ID-DocumentRecognition-SDK-Windows](https://github.com/MiniAiLive/ID-DocumentRecognition-SDK-Windows) | ID Document, Passport, Driver License, Credit Card, MRZ Recognition SDK |
| 3 | [ID-DocumentRecognition-SDK-Linux](https://github.com/MiniAiLive/ID-DocumentRecognition-SDK-Linux) | ID Document, Passport, Driver License, Credit Card, MRZ Recognition SDK |
| 4 | [ID-DocumentRecognition-SDK-Android](https://github.com/MiniAiLive/ID-DocumentRecognition-SDK-Android) | ID Document, Passport, Driver License, Credit Card, MRZ Recognition SDK |

### ID Document Liveness Detection SDK
| No | Project | Features |
|----|---------|-----------|
| 1 | [ID-DocumentLivenessDetection-SDK-Docker](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-SDK-Docker) | ID Document Liveness Detection SDK |
| 2 | [ID-DocumentLivenessDetection-SDK-Windows](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-SDK-Windows) | ID Document Liveness Detection SDK |
| 3 | [ID-DocumentLivenessDetection-SDK-Linux](https://github.com/MiniAiLive/ID-DocumentLivenessDetection-SDK-Linux) | ID Document Liveness Detection SDK |

### Web & Desktop Demo
| No | Project | Features |
|----|---------|-----------|
| 1 | [FaceRecognition-IDRecognition-Playground-Next.JS](https://github.com/MiniAiLive/FaceRecognition-IDRecognition-Playground-Next.JS) | FaceSDK & IDSDK Playground |
| 2 | [FaceCapture-LivenessDetection-Next.JS](https://github.com/MiniAiLive/FaceCapture-LivenessDetection-Next.JS) | Face Capture, Face LivenessDetection, Face Attributes |
| 3 | [FaceMatching-Windows-App](https://github.com/MiniAiLive/FaceMatching-Windows-App) | 1:1 Face Matching Windows Demo Application |

## About MiniAiLive
[MiniAiLive](https://www.miniai.live/) is a leading AI solutions company specializing in computer vision and machine learning technologies. We provide cutting-edge solutions for various industries, leveraging the power of AI to drive innovation and efficiency.

## Contact US
For any inquiries or questions, please contact us on [WhatsApp](https://wa.me/+19162702374).

<p align="center">
<a target="_blank" href="https://t.me/Contact_MiniAiLive"><img src="https://img.shields.io/badge/telegram-@MiniAiLive-blue.svg?logo=telegram" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://wa.me/+19162702374"><img src="https://img.shields.io/badge/whatsapp-MiniAiLive-blue.svg?logo=whatsapp" alt="www.miniai.live"></a>&emsp;
</p>
