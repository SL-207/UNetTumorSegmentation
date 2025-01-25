# U-Net Brain Tumor Segmentation
### Description and Notes
- Binary semantic segmentation of brain tumor scans
- U-Net architecture recreated and trained from scratch in PyTorch
- Trained total of 40 epochs
- Substantial improvement given lack of epochs (0% to 49.6% F1 score)
- Smoothed output mask after morphological post-processing

### Dataset
Cheng, Jun (2017). brain tumor dataset. figshare. Dataset. [https://doi.org/10.6084/m9.figshare](url)

### Model Architecture
![image](https://github.com/user-attachments/assets/8a946122-c6e0-478d-a099-0a60813abc18){: style="width:300px;"}

### Results
**Test Evaluation**
- Loss: 0.055
- F1 Score: 49.6%

**Train Validation performance**
<img width="864" alt="Screenshot 2024-10-04 at 8 02 37 PM" src="https://github.com/user-attachments/assets/40e2137a-ca0f-42f2-93cb-007fe91d4d79">


**Sample Inference Output**

<img width="717" alt="Screenshot 2024-10-04 at 7 43 08 PM" src="https://github.com/user-attachments/assets/391276ba-eb28-4c46-990c-a935ffffec9e">

<img width="714" alt="Screenshot 2024-10-04 at 7 43 56 PM" src="https://github.com/user-attachments/assets/659b570e-602f-4266-994c-9e4a67cdf6bc">
