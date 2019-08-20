Table of Contents
=================

   * [Personal Projects](#personal-projects)
      * [Hardware / OS Platform Used](#hardware--os-platform-used)
      * [Contents](#contents)
         * [Titanic Survival Prediction](#Titanic-Survival-Prediction)
         * [Startup data analysis(1st)](#Startup-data-analysis(1st))
         * [Startup data analysis(2st)](#Startup-data-analysis(2st))
         * [Startup data analysis(3st)](#Startup-data-analysis(3st))
         * [Startup data analysis(4st)](#Startup-data-analysis(4st))
         * [Otto group Prediction](#Otto-group-Predicton)

# Personal Projects

�� ����Ҵ� ���������� ������ ������Ʈ�� Kaggle�� �����ߴ� ������Ʈ,
������б� ��ǻ��������� ���п����� ������ ������Ʈ�� �����ϴ� ���Դϴ�. 
����� ������ ���Ǵ� �������� clarklimr@korea.ac.kr �� ���ֽø� �����ϰڽ��ϴ�.

This repository is a personal project, a project that participated in the Kagle,
It includes a project conducted by the Department of Big Data Convergence at Korea University.
Please fell free to contact me at clarklimr@korea.ac.kr

��� ������Ʈ �ڷῡ�� �����Ͱ� ������ ���� �뷮 ������ ������ �Ұ����ϱ� �����Դϴ�.

If some project material such as data are missing, it is not possible to upload because the data exceeded the file size limit or the data cannot be public.


## Portfolio

[PDF](https://github.com/clarklim/data_science_portfolio/blob/master/portfolio.pdf) (Updated 19.00.00)

�� ��Ʈ�������� ������Ʈ �� �Ϻθ��� ������ �ٷ�� �ֽ��ϴ�. �ڼ��� ������Ʈ �����̳� ���ϵǾ� ���� ���� ������ �� ����� ����Ҹ� ���ؼ� Ȯ�����ֽñ� �ٶ��ϴ�.

This portfolio covers briefly only some of my projects. Please check this repository for the details of the projects or the contents that are not included in this portfolio. 

## Hardware / OS Platform Used

- 13.3" Samsung Notebook9 2.5GHz Core i5-7200U, 8GB Ram
- Windows10
- Python 3.73 with `jupyter==1.0.0`
  - `numpy==1.16.2`
  - `pandas==0.24.2`
  - `sklearn==0.20.3`
  - `scipy==0.2.1`
  - `statsmodels==0.9.0`
  - `matplotlib==3.0.3`
  - `seaborn==0.9.0`
  - `lightgbm=2.3.1`
  - `tensorflow=1.9.0`
- R 3.5.3 with RStudio 1.1.463

## Contents

### Titanic Survival Prediction
(April 2019, Kaggle ������Ʈ)

- [Notebook](https://github.com/clarklim/data_science_portfolio/blob/master/titanic/PUBG%20Survival%20Time%20Prediction.ipynb) / [PDF](https://github.com/clarklim/data_science_portfolio/blob/master/titanic/pubg_summary.pdf)

- http://pubgtracker.com ���� �����ϴ� PlayerUnknown's Battleground�� ���� �÷��̾� �����Ϳ� �پ��� ����н� �˰����� �̿��Ͽ� Ư�� �÷��̾��� **������ ��� �����ð�**�� �����߽��ϴ�. ���� ������ ���� �߿� �������� Ž���Ͽ� ���� ������ ���� �� �ֵ��� �߽��ϴ�.

- Predicted the average survival time in a squad game using various statistical learning algorithms and the data of top PUBG players available at http://pubgtracker.com. Also, built survival strategies by exploring important variables identified in predictive algorithms.


### Mercedes-Benz Greener Manufacturing
(Jun 2017 - Jul 2017, Kaggle competition)


- [Notebook](https://github.com/otzslayer/data_science_portfolio/blob/master/Mercedes-Benz%20Greener%20Manufacturing/Mercedes-Benz%20Greener%20Manufacturing.ipynb)

- https://www.kaggle.com/c/mercedes-benz-greener-manufacturing

- �͸�ȭ�� �������� �̿��Ͽ� ������ �׽�Ʈ�� ����ϴ� ���� �ɸ��� �ð��� �����߽��ϴ�. ���� �ٸ� ���� ����(PCA, MCA ��)�� �� ������ �ٸ� �˰����� ����Ͽ� �� 18���� ���� ���� �������, �̸� ����ŷ�Ͽ� �ӻ�� ���� �����Ͽ����ϴ�. ĳ�� ����Ƽ�ǿ��� ���� 27%�� ����߽��ϴ�.

- Building the model using numerous anonymized features to predict that the time that the Mercedes-Benz car takes to pass testing. A total of 18 single models were created using different features sets (PCA, MCA, etc.) and three different algorithms. An ensemble model was implemented by stacked generalization and the result was of top 27% in leaderboard.

### Sberbank Russian Housing Market
(Jun 2017, Kaggle competition)

- [Notebook](https://github.com/otzslayer/data_science_portfolio/blob/master/Sberbank%20Russian%20Housing%20Market/Sberbank%20Russian%20Housing%20Market.ipynb)

- https://www.kaggle.com/c/sberbank-russian-housing-market

- ���� ������ �Ž� ���� �������� ����� �ε��� ������ �����߽��ϴ�. ������ �̻�ġ�� �������� ������� ���� ������ �ذ��ϱ� ���� ������ ��ó���� ���� �ð��� �Ҿ��Ͽ����ϴ�. �׶���Ʈ �ν��ð� ���� ������Ʈ�� ���� ���� �����ϰ�, ��������� �̿��Ͽ� �����Ͽ����ϴ�. ���� ����� ���� 25%�� ����߽��ϴ�.

- Forecasted realty prices by using housing data and macroeconomic patterns. Did extensive data preprocessing to alleviate problems that caused by a large number of outliers and some features with a lack of information. Implemented single models with gradient boosting and random forest, models were blended by weighted average with (0.8, 0.2). The result was of top 25% in leaderboard.

### Visitor Segmentation for Baik Nam June's Exhibition
(Jun 2017, (��)����)

- http://benple.com/?p=7140

- �ھƸ�, ������, �̰���, "IoT-based Omni Channel Service for Smart Exhibition and Value of Data", ICEC 2017, (2017).
	- **ICEC 2017 �ֿ������ ����**

- 2016�� 7������ 2016�� 12������ DDP���� ���� '�鳲�ؼ�'�� ��ư ���ͳ��� ����� ���� ������ ����ȸ�μ�, (��)������ ����� ����Ǿ����ϴ�. ��ǰ�� �Ҵ�� ��ư�� �������ν� ����Ʈ ���񽺸� ���� �� ������, �̸� ���� ���������� ���� �̿� ���¿� ���� �����͸� ���� �� �ֽ��ϴ�. ������ �����͸� ������� �м� ������ ���·� �����͸� ����, t-SNE�� k-��� �����м��� �̿��Ͽ� �������� �з��Ͽ����ϴ�. �� ����� ���� ���� ������ ��ġ�� Ÿ�� ������ � Ȱ���� �� �ֽ��ϴ�.

- The "Baik Nam June Show", which was held at DDP from July 2016 to October 2016, was the first exhibition in the world to be applied with "Button Internet". The docent service is provided to a visitor by pressing the button assigned to the artwork, and the service provider obtains the data that described the behavior pattern of the visitors. Based on the constructed database, the data was preprocessed in a form that can be analyzed, and then t-SNE and k-means clustering were conducted for the visitor segmentation. This result can be used for attracting visitors and target marketing in the follow-up exhibition.

### Predicting the House Price in King County
(Feb 2017, ���� ������Ʈ)

- [Notebook](https://github.com/otzslayer/data_science_portfolio/blob/master/King%20County%20House%20Price/House_KC.Rmd)

- �ŷ���, ������ �� ����, ��ġ ���� ���� �̿��Ͽ� �þ�Ʋ ŷ ī��Ƽ ������ ���� ������ �����߽��ϴ�. �кλ� ���ǿ����� �����ߴ� ������Ʈ��, Adaptive Lasso�� ������ �پ��� ȸ�� �м� �˰����� ����߽��ϴ�.

- Predicted the house price in King County, Seattle using transaction dates, features of housing, and location information. This project that was conducted for undergraduate lectures, using a variety of regression analysis algorithms, including Adaptive Lasso.

### Ensemble Approach for Financial Prediction
(Jun 2016 - Dec 2016, �ټ� �ܱ��� ���� �ְ� ������Ʈ)

- [Keynote](https://github.com/otzslayer/data_science_portfolio/blob/master/Ensemble%20Approach%20for%20Financial%20Prediction/Ensemble%20Approach%20for%20Financial%20Prediction.pdf) / [Thesis](http://dcollection.khu.ac.kr.openlink.khu.ac.kr:8080/common/orgView/000000204945)

- �پ��� ���� ����� �ְ� ���� �� ȯ�� ���� ������ �̿��Ͽ� ���� ������ �����Ͽ����ϴ�. ���� ������ �ٸ��� ������ �α� ���ͷ��� �Է� ������ �Ͽ� ���� �����߽��ϴ�. ���� ���� �ӻ���Ͽ� ������ ���̰�, Lasso�� �̿��Ͽ� ���� �𵨿����� ������ �����ϰ� �߽��ϴ�.

- Forecasted the financial market by using the stock market indices, exchange rates based on various contries. Unlike previous studies, the model was implemented with the logarithmic return of the index as input variable. Improved the performance by ensembling single models, and use Lasso to explain the feature importance of each variable.

- ������, �̰���, ������ ���� ������ ���� �ӻ�� ����: ����ŷ�� �Ѹ� �����츦 �߽����Ρ�, 2017 �� �ѱ����������ý�����ȸ �߰��м���ȸ����, (2017).
- ������ �� 3 ��, ������н��� �Ѹ� ������ ����� Ȱ���� �ֽĽ��� �� ȯ�� ���� �� ������, 2017 �� �ѱ����������ý�����ȸ ����м���ȸ����, (2017).

### Korea Earthquake Interactive Map
(Dec 2016, ���� ������Ʈ)

- [Link](https://otzslayer.shinyapps.io/kor_quakes/) / [PDF](https://github.com/otzslayer/data_science_portfolio/blob/master/Korea%20Earthquake%20Interactive%20Map/Paper/ShortPaper.pdf)

- ���û�� ���� �����͸� �ǽð����� �ε��ϰ� Shiny�� �̿��Ͽ� ���ͷ�Ƽ�� ������ �����߽��ϴ�. (���� ���û ����Ʈ�� ������ �������� �ùٸ��� �����͸� �޾ƿ��� ���� �ӽ������� csv ������ �ҷ������� �߽��ϴ�.) ������ ���͸� ����� ���� �����̴��� �پ��� �׷��� ��ҵ��� �����մϴ�.

- Implemented an interactive map, which described real-time earthquake data provided by Korea Meteorological Administration, using Shiny. (It is now temporarily importing the csv file due to the fact that the site was not able to receive the correct data because of the domain change of the site.) It provides a slider with data filtering function and various graphic elements.

### Network Analysis for Football Transfer Market
(Dec 2016, ���� ������Ʈ)

- [Code](https://github.com/otzslayer/data_science_portfolio/blob/master/Network%20Analysis%20for%20Football%20Transfer%20Market/Network%20Analysis%20for%20Football%20Transfer%20Market.Rmd) / [PDF](https://github.com/otzslayer/data_science_portfolio/blob/master/Network%20Analysis%20for%20Football%20Transfer%20Market/ShortPaper.pdf)

- ��Ʈ��ũ �м��� ���� 2016�� ���� ���� �౸ ���������� �ٶ󺸾ҽ��ϴ�. ������ �Ը� ���� ū �� ���� ���׿� �ֱ� 3�Ⱓ ���� ������������ ������ ������ �߽����� ����ġ ��Ʈ��ũ �м��� �õ��߽��ϴ�. �� ��� ��Ʈ��ũ�� ���� ���� ������ ���Ģ(power law)�� ������, ���� �߽ɼ��� ���ؼ� �ױ۷��� �����̾���� ������� �ſ� ũ�ٴ� ����� Ȯ���߽��ϴ�.

- I looked at European football transfer market in the summer of 2016 through the network analysis. I've trided to analyzed the weighted networks around the four largest leagues and the teams that have competed in the UEFA Champions League for the past three years. As a result, i found that the distribution of network connectivity follows the power law and that the English Premier League is influential through eigenvalue centrality.

### Kobe Bryant Shot Selection
(Apr 2016, Kaggle competition)

- [RMarkdown](https://github.com/otzslayer/data_science_portfolio/blob/master/Kobe%20Bryant%20Shot%20Selection/Kobe%20Bryant%20Shot%20Selection.Rmd) / [Keynote](https://github.com/otzslayer/data_science_portfolio/blob/master/Kobe%20Bryant%20Shot%20Selection/Keynote.pdf) / [Short Paper](https://github.com/otzslayer/data_science_portfolio/blob/master/Kobe%20Bryant%20Shot%20Selection/Paper/Paper.pdf)

- https://www.kaggle.com/c/kobe-bryant-shot-selection

- NBA�� ���� API���� �����ϴ� �����͸� �̿��Ͽ� NBA�� ������ �ں� ����̾�Ʈ�� �� ���� ���θ� �����߽��ϴ�. �󱸿� ���� ������ ������ �̿��Ͽ� ���� �������� �����Ͼ�Ͽ���, �׶���Ʈ �ν����� ����Ͽ� �𵨸��߽��ϴ�. ���� ����� ���� 6%�� ����߽��ϴ�.
- Using data provided by the NBA's official API, I predicted that which shots by Kobe Bryant, who is the legendary player of LA Lakers, will find the bottom of the net. Using domain knowledge of basketball, many variables were engineered and implemented using gradient boosting. The final result was the top 6%.