# EE5179 - July November 2022 -  IIT Madras

Instructor - [Prof. Kaushik Mitra](https://www.ee.iitm.ac.in/kmitra/)
Teaching Assistant - K Vikas Mahendar

All tutorials and assignments will be hosted on this repository. Each folder corresponds to the tutorial based on concepts taught in the corresponding week. 

## Submission instructions

Once completed, students have to submit their solutions via IITM-Moodle (courses-new). Please submit your notebooks in PDF format. 

## Convert .ipynb to .PDF

Please paste the following cell onto your completed notebook to generate the submission pdf file. 

```python
!pip install nbconvert
!sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
!jupyter nbconvert --to html "/content/drive/MyDrive/Colab Notebooks/filename.ipynb"
```
