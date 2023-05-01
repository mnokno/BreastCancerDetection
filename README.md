# BreastCancerDetection
Brest cancer detection from MRI scans and patient details using custom CNN architecture.

Data Sets: 
- https://www.kaggle.com/datasets/mnokno/train-images-processed-256/settings
- https://www.kaggle.com/competitions/rsna-breast-cancer-detection/data

Prediction are made per breast based on:
- scans: The mammograms, in dicom format.
- site_id: ID code for the source hospital.
- patient_id: ID code for the patient.
- image_id: ID code for the image.
- laterality: Whether the image is of the left or right breast.
- view: The orientation of the image. The default for a screening exam is to capture two views per breast.
- age: The patient's age in years.
- implant: Whether or not the patient had breast implants. Site 1 only provides breast implant information at the patient level, not at the breast level.
- density: A rating for how dense the breast tissue is, with A being the least dense and D being the most dense. Extremely dense tissue can make diagnosis more difficult. Only provided for train.
- machine_id: An ID code for the imaging device.

Kaggle Competition: https://www.kaggle.com/competitions/rsna-breast-cancer-detection