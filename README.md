# EE5179

All tutorials and assignments will be hosted on this repository. 

## Convert .ipynb to .PDF

Please paste the following cell onto your completed notebook to generate the submission pdf file. 

```python
!pip install nbconvert
!sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
!jupyter nbconvert --to html "/content/drive/MyDrive/Colab Notebooks/filename.ipynb"
```
