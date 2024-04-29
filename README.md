# FL_Breast_Cancer_Classification
### Federated Learning in Cancer Diagnosis
Federated Learning based Breast  Cancer Classification
**Why Federated Learning?**
1. **Improves model training on large distributed data:** Federated learning allows for the collaborative training of machine learning models across multiple decentralized datasets, enabling the development of more robust models without centralizing sensitive data.
2. **Preserves privacy of the data:** With federated learning, data remains decentralized, and only model updates are shared among participating entities, ensuring that sensitive medical data, such as cancer diagnosis images, remains secure and private.
3. **Increases model variance:** Federated learning enables training on diverse datasets from various medical centers, which can improve the generalization and robustness of the model, leading to more accurate predictions.

**Why on Cancer Data?**
1. **Novelty in non-IID case:** Federated learning on cancer data, particularly in a non-IID (non-identically distributed) setting, presents a novel application of the technology in the medical domain.
2. **Variety of breast cancer types:** Breast cancer encompasses various subtypes, each requiring distinct treatment approaches. Training models on diverse datasets allows for more accurate predictions across different cancer types.
3. **Preservation of privacy:** Medical imaging data, such as breast cancer histopathological images, is highly sensitive and should not be shared outside of hospitals for privacy reasons. Federated learning enables collaboration between medical institutions without compromising patient privacy.
4. **Collaborative model training:** Hospitals can collaborate in training models using federated learning without sharing raw data, leading to improved model accuracy for all collaborating institutions.

**Datasets Used:**
- **BreakHis Dataset:** A collection of microscopic images of breast tumor tissue, containing benign and malignant samples from 82 patients.
- **BCI Dataset:** Image pairs covering a range of HER2 expression levels in breast cancer immunohistochemical images.

**Type of Computing Resources:**
1. **University at Buffalo's Center for Computational Research (CCR):** High-performance computing resources for training and testing machine learning models.
2. **Google Colab Pro:** Cloud-based platform for testing the architecture of machine learning models.

**Additional Work:**
1. **Implementation of FL algorithms:** Testing and comparing various federated learning algorithms and evaluating their performance based on predefined metrics.
2. **Testing on non-IID datasets:** Ensuring the robustness and effectiveness of federated learning approaches when dealing with datasets collected from different medical centers with varying imaging equipment and demographic characteristics.

*For more details, refer to the corresponding publications and dataset repositories.*

---
**References:**
- Spanhol, F., Oliveira, L. S., Petitjean, C., & Heutte, L. (2016). A dataset for breast cancer histopathological image classification. IEEE Transactions of Biomedical Engineering.
- Liu, S., Zhu, C., Xu, F., Jia, X., Shi, Z., & Jin, M. (2022). BCI: Breast Cancer Immunohistochemical Image Generation through Pyramid Pix2pix. ArXiv preprint arXiv:2204.11425.
