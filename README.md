# ML4TR
Machine Learning 4 Trial Registries

This repository lists the Jupyter Notebooks used on Google Colab for the following article submitted to [JAMIA Open](https://academic.oup.com/jamiaopen)

# Machine learning Methods for Creating and Updating Registers of Randomized Controlled Trials

Authors:<br> 
[Frank Soboczenski](https://h21k.github.io/) School of Population Health and Life Sciences, King's College London, London, UK<br>
[Anna Noel-Storr](https://www.rdm.ox.ac.uk/people/anna-noel-storr) Radcliffe Department of Medicine, Medical Sciences Division, University of Oxford, Oxford, UK<br>
[Fenton, Candida](https://www.ed.ac.uk/profile/candida-fenton) University of Edinburgh, Cochrane Vascular Group; Usher Institute<br>
[Cheyne, Joshua](https://www.gla.ac.uk/researchinstitutes/icams/staff/index.html/staffcontact/person/4edce9ec829f) University of Glasgow, Institute of Cardiovascular & Medical Sciences<br>
[Stovold, Elizabeth](https://www.sgul.ac.uk/profiles/elizabeth-stovold) St George’s, University of London, Cochrane Information Specialist, Cochrane Airways Group<br>
[Hampson, Lynn](https://www.liverpool.ac.uk/life-course-and-medical-sciences/staff/lynn-hampson/) University of Liverpool, Institute of Life Course and Medical Sciences<br>
[James Thomas](https://iris.ucl.ac.uk/iris/browse/profile?upi=JTHOA32) UCL Institute of Education, University College London, London, UK<br>
[Byron C Wallace](http://www.byronwallace.com/) College of Computer and Information Science, Northeastern University, Boston, USA<br>
[Iain J Marshall](https://kclpure.kcl.ac.uk/portal/iain.marshall.html) School of Population Health and Life Sciences, King's College London, London, UK<br>

## Structure of the repository

### Data 
Currently the data can not be made available here. Please contact us for individual requests.

### Machine Learning Methods
The following models have been used with this study:

#### Support Vector Machines (SVMs)

- `SVM` (for each trial register with hyperparaeters set according to [previous work](https://kclpure.kcl.ac.uk/portal/files/86954073/Marshall_et_al_2018_Research_Synthesis_Methods.pdf)

#### Convolutional Neural Networks (CNNs)

- `CNN` (for each trial register with hyperparaeters set according to [previous work](https://kclpure.kcl.ac.uk/portal/files/86954073/Marshall_et_al_2018_Research_Synthesis_Methods.pdf)

#### Transformer Models

- `BERT Tensorflow` (Google) - with max token length of 128 
- `BERT PyTorch` (Google, Huggingface) - with max token length of 512 
- `SciBERT PyTorch` (Huggingface + Allen.AI weights) - with max token length of 512
- `BioBERT PyTorch` (Huggingface) `Excluded for the moment!`
