# Mask Detection in Public
![source:https://iblnews.org/wp-content/uploads/2019/11/intelAI.jpg](https://iblnews.org/wp-content/uploads/2019/11/intelAI.jpg)

## Project Showcase: Mask Detection in Public

## Preface:
In early 2020, Coronavirus disease (COVID-19) outbreak. The virus is highly contagious through respiratory droplets produced when an infected person coughs or sneezes. For the reason, many Asia country's governments has regulated people to wear masks in public places. In the situation, the mask detection app based on AI edge computing device might be a useful tool for supporting the policy.

## Ideal Application:
Through AI OpenVINO toolkit, develop an effective model to detect whether people wear masks correctly or not in the public.

Ideal Example Demo (Based on the Mask Detection results, show different colors of square):

(※ Yellow: wear in corret way, Blue: not wear a mask, pink: wear incorrectly) 

![source:https://raw.githubusercontent.com/chenkenanalytic/OpenDevLibrary/master/demo_files/images/target.jpg](https://raw.githubusercontent.com/chenkenanalytic/OpenDevLibrary/master/demo_files/images/target.jpg)

Original Open Resources: https://www.facebook.com/groups/525579498272187/permalink/642268049936664/

## Actual Development Result
![source:https://raw.githubusercontent.com/chenkenanalytic/OpenDevLibrary/master/demo_files/images/FACE-output.png](https://raw.githubusercontent.com/chenkenanalytic/OpenDevLibrary/master/demo_files/images/FACE-output.png)

## Project To-Dos

1. Apply orignial model to transfer learning and fine tuning on "Mask Detection Dataset" (open-source dataset)
2. Adopt softmax activation function for detecting different situations of wearing masks
3. Deploy on edge devices to realize edge computing

## REFERENCES:
### Intel's Official Installation Guide for OpenVINO on linux: 
[https://docs.openvinotoolkit.org/latest/_docs_install_guides_installing_openvino_linux.html#install-openvino]

### Model used in Demo.ipynb i.e. face-detection-retail-0005
[https://docs.openvinotoolkit.org/latest/_models_intel_face_detection_retail_0005_description_face_detection_retail_0005.html]

### Open Source Dataset
[https://www.facebook.com/groups/525579498272187/permalink/642268049936664/]
