# Fishmonger
Models and results of Fishmonger project

## Details
- Fishmonger model made using PyTorch, with YOLOv5 as a base
- Final model consists of 2 types:
  - **Object detection**: using Fishnet.AI Dataset
  - **Instance segmentation**: using a combination of Fishnet.AI and independently-collected data
- Models were trained using different scenarios due to time constraints during the making of the project
- Training scenario for **Instance segmentation** model:\
  ![image](https://github.com/TimothyPanggabean/Fishmonger/assets/63400872/37d35b4e-1927-4269-8742-3a97596f0d16)
- Training scenario for **Object detection** model:\
![image](https://github.com/TimothyPanggabean/Fishmonger/assets/63400872/91c28e08-45f8-447f-ba5a-ec0363409403)
- Final model can be used to detect:
  - **Object detection**: albacore, bigeye tuna, blue marlin, escolar, great barracuda, long snouted lancetfish, mahi mahi, opah, shark, shortbill spearfish, skipjack tuna, striped marlin, swordfish, tuna, wahoo, and yellowfin tuna
  - **Instance segmentation**: tuna, cakalang, tongkol, squid, human, and unknown
