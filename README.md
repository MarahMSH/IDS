# IDS

1- The Phishin_email dataset is too large i was unable to upload it to github here is a drive link for it

https://drive.google.com/file/d/1UY0cumK0iFRM19Ql2kF8Rg4AD58hRmS6/view?usp=sharing

2- To run the code use the colab (cloud-based python environment) and connect it to your actual hardware resources.

3- Connect your colab with your google drive that you should upload datasets on, using this code:

from google.colab import drive
drive.mount('/content/drive')

4- Run the code sequentially exactly as provided in the actual code, but you have to change the path for each dataset based on your drive path:

- smsspam_DS=pd.read_csv('/content/drive/MyDrive/DATASET/smsspamcollection.tsv',sep='\t') # change the path 
- Phishing_DS = pd.read_csv('/content/drive/MyDrive/DATASET/Phishing_Email.csv') # change the path
- spambase_DS=pd.read_csv('/content/drive/MyDrive/DATASET/spambase.csv') # change the path 

