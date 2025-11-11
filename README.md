# ITD – Indian Traffic Dataset

The **ITD (Indian Traffic Dataset)** is a large-scale dataset designed to advance research in **traffic video analytics** for Indian road environments.  
It captures the complex and heterogeneous traffic conditions found across India, enabling tasks such as **turning movement counts**, **lane-based behavior analysis**, and **violation detection**.

---

## Dataset Overview

| Property | Description |
|-----------|--------------|
| **Name** | ITD – Indian Traffic Dataset |
| **Scope** | Multi-class, multi-location dataset for traffic flow analysis and computer vision model training |
| **Scale** | 250,000+ labeled objects, 9,000+ annotated images |
| **Coverage** | 25+ diverse locations across **14 states/UTs** in India |
| **Data Type** | Annotated traffic images and video frames |
| **Applications** | Object detection, vehicle classification, traffic flow modeling, violation and safety analysis |
| **Annotation Standard** | Indo-HCM (Indian Highway Capacity Manual) based classification |
| **Image Conditions** | Day, night, urban, highway, and expressway scenes under varied weather and density conditions |

---

## Regional Diversity

The dataset spans:
- Expressways  
- National and State Highways  
- Major District Roads  
- Arterial and Urban routes  

This diversity ensures high model robustness to Indian traffic heterogeneity.

![ITD Spatial Diversity](https://github.com/teg-iitr/ITD-Indian-traffic-dataset/assets/7382380/b8950168-f7fb-46b1-b2b4-15f5e2c46099)

---

## Object Categories

The dataset follows Indo-HCM vehicle classification and covers key road-user categories such as:
- Two-Wheelers  
- Auto Rickshaws  
- Cars / Jeeps / Vans  
- Light Commercial Vehicles  
- Buses  
- Trucks / HCVs  
- Bicycles
- Pedestrians  

![2023-05-23_16h44_17](https://github.com/teg-iitr/ITD-Indian-traffic-dataset/assets/7382380/f4402b7c-5a6a-4cfa-a507-5f341046a04a)

> **Note:** Serial No. 7 and 16 in the class mapping correspond to relabeled images from [IDD Dataset](https://idd.insaan.iiit.ac.in/dataset/details/).

---

## Results Summary

### Object Detection Performance
| Metric | Value |
|---------|--------|
| **mAP (50)** | 0.91 |
| **Precision** | 0.87 |
| **Recall** | 0.86 |

---

## License

The pretrained models are released under the:

> [Creative Commons Attribution-NonCommercial 4.0 International License](./LICENSE)  
> You are free to share and adapt the data for **research and non-commercial purposes**,  
> provided appropriate credit is given to the original authors.

**Citation / Acknowledgment**  
> If you use this dataset or derivative models, please cite:  
> *"ITD – Indian Traffic Dataset (2024), IIT Roorkee, India."*

---

## Access Request

The dataset is currently available for **research use upon request**.
[ITD Models Download Link](https://quirrelhk.github.io/model-download-page/)