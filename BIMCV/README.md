# Dataset Description

## General Description

* **Name** BIMCV-COVID19+
* **Detailed Description**  BIMCV-COVID19+ dataset is a large dataset with chest X-ray images CXR (CR, DX) and computed tomography (CT) imaging of COVID-19 patients along with their radiographic findings, pathologies, polymerase chain reaction (PCR), immunoglobulin G (IgG) and immunoglobulin M (IgM) diagnostic antibody tests and radiographic reports from Medical Imaging Databank in Valencian Region Medical Image Bank (BIMCV). The findings are mapped onto standard Unified Medical Language System (UMLS) terminology and they cover a wide spectrum of thoracic entities, contrasting with the much more reduced number of entities annotated in previous datasets. Images are stored in high resolution and entities are localized with anatomical labels in a Medical Imaging Data Structure (MIDS) format. In addition, 10 images were annotated by a team of expert radiologists to include semantic segmentation of radiographic findings. Moreover, extensive information is provided,including the patient’s demographic information, type of projection and acquisition parameters for the imaging study, among others. This first iteration of the database includes 1380 CX, 885 DX and 163 CT studies
* **Source** Medical Imaging Database of Valencia Region
* **Dataset Size** 70GB
* **Sample Size** 5381 images, 1311 patients
* **Type of Dataset** Images
* **Tags** COVID19, CXR, Chest X-ray, CT, pneumonia, alveolar pattern
* **Licence** https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/bimcv-covid19-dataset-research-use-agreement-2/ 
* **Paper Publised** https://arxiv.org/pdf/2006.01174.pdf
* **Task** This dataset can be used to generate models which can identify COVID19 patients from CXR and CT scans
* **URL to download** bimcv.cipf.es/bimcv-projects/bimcv-covid19/ 

## Metadata
* **Session ID**

* **Patients Identifiers**
  * **Patient ID**
  * **Study Date**
  * **Age**
  * **Sex**
  * **Test** : PCR/IGG/IGM/...
  * **Result:** Positive/Negative

* **Disease Profile**
  * **Name** COVID
  * **Region Affecting the body** Lungs

* **Imaging Reports**
  * **Type of Exam** RX or CT scans
  * **Part of the body** Lungs
  * **Date of Exam**
  * **Report** Radiology report (in Spanish), radiological findings, differentialdiagnosis and locations as extracted using natural language processing from theradiology report.
  * **Clinical History** Date and result of diagnostic tests
  * **Labels** COVID 19/alveolar pattern/interstitial pattern/pneumonia /....
  * **Locations** costophrenic angle/lobar/bilateral/lower lobe/...
