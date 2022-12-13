## 👨‍💻 Built with
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" /> <img src="https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white" />

##  Descripction about project
OLX SCRIPT made for searching in a category from given link. 

Need to give a link to category we are interested and also list of searching tags.

After bot finishes scrapping we will get a DataFrame with columns: 'name' 'price' 'url'

## ⚙️ Before use you should change values in variables:
```bash
SEARCH_TAGS = ['LIST','OF','INTERESTING','SEARCHTAGS']
driver = webdriver.Chrome('PATH/TO/LOCATION/chromedriver')
driver.get('LINK_TO_CATEGORY_ON_OLX') 
```
