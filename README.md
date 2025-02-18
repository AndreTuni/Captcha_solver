# CAPTCHA Recognition Challenge

## Motivation
A CAPTCHA (Completely Automated Public Turing test to Tell Computers and Humans Apart) is a commonly used feature in web applications to block non-human access. CAPTCHAs help prevent spam on websites, such as promotion spam, registration spam, and data scraping. Bots are less likely to abuse websites with spamming if those websites use CAPTCHA. Many websites use CAPTCHA to prevent bot raiding, and it works effectively. The design of CAPTCHA ensures that humans can complete them, while most robots cannot.

## Dataset
- **Dataset Size**: 14,860 images.
- **Format**: Two datasets divided into train and test sets, with the label embedded in the image name (contains 4 or 5 characters):
  - **Soft dataset**: Consists of simpler CAPTCHAs. Students must start the project with this dataset.
  - **Hard dataset**: Consists of CAPTCHAs with added distortions to make identification more difficult.
- **Download Link**: [Dataset](https://uporto-my.sharepoint.com/:f:/g/personal/up488707_up_pt/EnnrytvkVKlPuQ9qDoS7tpQBuRJ_Pecv_zWi_-9LSxC2lw?e=4GHGLo)

## Challenge
1. **Propose a custom AI model** that decodes CAPTCHA images with 4 and 5 character encodings. The CNN model needs to be designed, implemented, and trained (no fine-tuning approaches should be applied).
2. **Evaluation Metrics**:
   - Train and test accuracy
   - Confusion matrix
   - Other evaluation methodologies (e.g., histograms, model complexity)
3. **Discussion**:
   - Analyze the results of your approach.
   - Discuss limitations and potential improvements.

