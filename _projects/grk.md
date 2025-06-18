---
title: Intraoperative Multi-Sensor Tissue Differentiation in Oncology
layout: page
# description: Intraoperative Multi-Sensor Tissue Differentiation in Oncology
permalink: /projects/grk/

---

- Funding: German Research Foundation, project ID 40947457.
- PIs: Oliver Sawodny (University of Stuttgart), Arnulf Stenzl (University Hospital Tübingen)
> 🔗 **Related Publications**  
> See [Biomedical Engineering Publications](/publications/#biomedical-engineering-publications)

In oncology, the differentiation between healthy and tumorous tissue is crucial for improved diagnostics, complete tumor removal, and better patient outcomes. The current gold standard, the histopathological instantaneous section, comes with a time delay due to the need to remove tissue, transport it to and examine it in a laboratory. Since tumors often differ physically from surrounding tissue, introducing real-time sensor systems in surgery can help guide decisions directly in the OR. A short review of this topic is available [here](https://doi.org/10.1109/EMBC53108.2024.10782728).

My PhD topic was *impedance-based tissue differentiation for bladder tumor detection*, and most of my works focus on this topic. After finishing my PhD, I have been a group leader within the overall project and supervise projects dealing with impedance sensor arrays, data-driven sensor fusion, and intraoperative navigation and localisation based on endoscopic videos.

---

## Impedance-based tissue classification
Bladder tumor recurrence remains a major challenge in uro-oncology, increasing both risk and cost of patient care.
Bladder tumors do not only differ visually from healthy tissue, but also in their electrical properties due to an altered physiology. A possible base for intraoperative tissue differentiation are impedance measurements, which are, however, difficult to obtain passing through the limited space of the urethra. 

Highlights of my work are:
- Developed and validated a **minimally invasive impedance sensor** (Ø 2 mm) suitable for transurethral insertion during bladder endoscopy ([📄 key publication](https://doi.org/10.1109/JSEN.2021.3108779))  
- Created **multi-physical tissue models**, especially to connect the intertwined mechanical and electrical domains in the context of sensor-based tissue differentiation ([📄 key publication](https://doi.org/10.1109/TBME.2022.3199468)).
- Designed and evaluated a **patient-specific machine learning pipeline** for tissue classification robust to deformation, tumor types, and radiotherapy artifacts ([📄 key publication](https://doi.org/10.1038/s41598-024-84844-9))


Recent directions within our group extend this work to **multi-electrode sensor arrays** provinding a spatial resolution of the measurement area.

---
## Sensor fusion
<!-- To increase the confidence and robustness of sensor prediction, our goal is to fuse sensors from different physical domains.
There are several challenges when it comes to multimodal systems, such as limited measurement time, different spatial resolution (pointwise vs. wide-field), or tissue deformation making some modalities unreliable. To address this, our work includes:
- Cross-modal translation and feature alignment, aiming for knowledge transfer from a strong to a weak modality during training to enhance unimodal performance of the weak modality at inference ([📄 publication](https://doi.org/10.1109/SENSORS60989.2024.10784632)).
- Entropy-based sensor placement and fusion strategies to combine pointwise impedance measurements with wide-field hyperspectral imaging (submitted to IEEE Sensors 2025)
- Multi-physical tumor modeling for better understanding and model-based investigations (to be presented at IEEE EMBC 2025) -->
Combining sensors from different physical domains increases prediction robustness and offers redundancy — but comes with challenges such as variable resolution, deformation, or differing acquisition rates.

Key developments:
- Cross-modal translation and feature alignment, aiming for knowledge transfer from a strong to a weak modality during training to enhance unimodal performance of the weak modality at inference ([📄 publication](https://doi.org/10.1109/SENSORS60989.2024.10784632)).
- Entropy-based sensor placement and fusion strategies to combine pointwise impedance measurements with wide-field hyperspectral imaging (submitted to IEEE Sensors 2025)
- Multi-physical tumor modeling for better understanding and model-based investigations (to be presented at IEEE EMBC 2025)

---

## Intraoperative navigation and localization
<!-- In the context of bladder cancer surgeries, another big issue arises from the limited field of vision through the endoscope. Robust feature extraction is fundamental for locating abnormalities in the urinary bladder, ensuring precise orientation within the hollow organ. Blood vessel provide a unique structure to help train localisation and navigation algorithms within the bladder. To address this, our work includes:
- Simultaneous description and detection of sparse features in the deformable intraoperative bladder environment ([📄 publication](https://doi.org/10.1109/SENSORS60989.2024.10785221)).
- Improved datasets and algorithms for bladder vessel segmentation (to be presented at IEEE EMBC 2025). -->
Bladder surgery is constrained by limited visibility through endoscopes. Reliable **feature extraction** is essential for orientation and navigation within the hollow organ. Blood vessels offer a robust and unique structure for geometric mapping.

Key developments:
- **Sparse feature detection and localization** in the deformable bladder environment ([📄 publication](https://doi.org/10.1109/SENSORS60989.2024.10785221))  
- Improved datasets and segmentation algorithms for **blood vessel recognition** (to appear at *IEEE EMBC 2025*)

---

_Last updated: June 2025_