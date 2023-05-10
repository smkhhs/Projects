<p align="center">
  <img width="500" src="https://news.mediaheroes.com.au/hubfs/market-segmentation-media-heroes-banner.webp" alt="logo">
</p>

<h1 align="center">Customer Segmentation using Python :two_men_holding_hands: </h1>

<h2 align="center">EDA - K Means - PCA</h2>

### :scroll: Basic Overview
Customer segmentation is the process of organizing customers into specific groups based on shared characteristics, behaviors, or preferences, with the aim of delivering more relevant experiences.

This project aims to perform Clustering / Segmentation on the dataset and identify popular customer groups along with their definitions/rules, followed by location-wise analysis to identify regional trends in India and transaction-related analysis to identify interesting trends that can be used by a bank to improve / optimize their user experiences.

This project has been completed within Jupyter Notebooks using the Python programming language. You can run these notebooks using an appropriate IDE/UI, such as  _Jupyter Notebook_  or _JupyterLab_.

The model notebook included in this repository has already been executed in full, with all relevant plots, figures and results already visible. Therefore, the fully executed file can be viewed by clicking on the file name directly on GitHub.

### :two_men_holding_hands: Importance of Customer Segmentation

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1400/1*fOJTsYz4R287IVC_j4qi0Q.gif" height="200">
</p>

Customer segmentation plays an important role in the market and aids in customer success inturn improving the Business. The major 5 benefits of market segmentation are Determining market opportunities, Adjustments in marketing appeals, Developing marketing programs, Designing a product, Media selection which is the major and the most important of them all.
#### Business : 
Dividing your target audience into groups – customer segments – grants insight into every aspect of your operation. Customer segmentation helps businesses earn greater market share, identify their best customers, and then reach those customers through their most effective channels.
#### Market :
Segmentation helps marketers to be more efficient in terms of time, money and other resources. Market segmentation allows companies to learn about their customers. They gain a better understanding of customer's needs and wants and therefore can tailor campaigns to customer segments most likely to purchase products.

----
<font size=5>**:warning: Note :clock5:**</font> 
The code takes a considerable amount of time to run given the size of data

----
### :black_nib: Preparation 
**Reading the Data Set**
Code notebook has a path variable as shown below to set the directory of the data set. Prefix the location of the data set on your PC to / or store the data in the same folder as your notebook.
```python
# Importing Dataset
df = pd.read_csv('path/model_data.csv')
```
**Load the packages**
Most of the packages are pre installed during Anaconda installation. If any package is not  installed on your PC, please follow the steps by replacing the package name with the required package.
```
conda install -c conda-forge <package_name>
pip install <package_name>
```
You can run the whole file by pressing _F5_ button or run selected block of cells, using _F9_.

---
