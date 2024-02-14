BD-Net 

BD-Net是一种基于人工智能深度学习技术的网络模型，其设计宗旨是利用临床数据和乳腺超声检查的BI-RADS描述符来预测通过超声检测到的女性乳腺癌。该网络模型由两部分数据集A和B训练而来，并对其性能进行了在外的测试集上评估。
BD-Net的功能主要包括以下几点：
1. **高准确性**：在数据集A的训练数据上，BD-Net达到了92.5%的准确率，这意味着它在预测乳腺癌方面具有很高的可靠性。
2. **高敏感性和特异性**：BD-Net在敏感性和特异性方面表现出色，分别为93.0%和92.1%。这表明模型在识别乳腺癌病例方面既不会漏诊太多也不会误诊太多。
3. **强预测能力**：BD-Net在数据集A上的AUC（曲线下面积）值为0.97，表明其具有很强的阳性预测能力，能够很好地区分良性和恶性乳腺病变。
4. **实际应用效果**：在外的测试集上，BD-Net也展示了良好的性能，其AUC值为0.92，敏感性和特异性分别为93.8%和91.0%，证明了其不仅在训练数据上而且在实际应用中也是有效的。
5. **与专业放射学家相比较**：与放射学家使用BI-RADS超声标准进行分类的结果相比，BD-Net的性能在某些指标上与放射学家相近，甚至在某些情况下更优。
综上所述，BD-Net通过深度学习技术在预测超声检测到的女性乳腺癌方面提供了准确、可靠的辅助工具，有潜力改善乳腺癌的诊断过程，帮助放射科医生更好地进行病变的鉴别诊断。

BD-Net is an AI-based deep learning network model designed to predict female breast cancer detected by ultrasound using clinical information and Breast Imaging Reporting and Data System (BI-RADS) ultrasound (US) descriptors. The model was trained on two datasets (A and B), which were derived by selecting different variables, and its performance was evaluated on an external test set.
The functions of BD-Net include:
1. **High Accuracy**: On the training dataset A, BD-Net achieved an accuracy of 92.5% (95%CI, 90.5–94.2), indicating a high level of reliability in predicting breast cancer.
2. **High Sensitivity and Specificity**: BD-Net performed well in terms of sensitivity and specificity, reaching 93.0% (95%CI, 90.3–95.4) and 92.1% (95%CI, 89.7–94.6) respectively. This suggests that the model has a high ability to identify cases of breast cancer without missing too many diagnoses or making too many misdiagnoses.
3. **Strong Predictive Ability**: BD-Net demonstrated a strong predictive capability with an AUC (Area Under Curve) value of 0.97 on dataset A, indicating a good ability to distinguish between benign and malignant breast lesions.
4. **Real-World Application Performance**: On the external test set, BD-Net also showed good performance with an AUC of 0.92, sensitivity of 93.8% (95%CI, 87.5–98.8), and specificity of 91.0% (95%CI, 85.0–96.0), proving its effectiveness not only on training data but also in real-world applications.
5. **Comparison with Radiologists**: When compared to radiologists' predictions using BI-RADS ultrasound criteria, BD-Net's performance was similar to or even superior in some cases.
In summary, BD-Net provides an accurate and reliable assistive tool for predicting breast cancer detected by ultrasound in women, which has the potential to improve the process of breast cancer diagnosis and assist radiologists in better differential diagnosis of lesions.

The study has been published, https://www.sciencedirect.com/science/article/pii/S2949668323000137
