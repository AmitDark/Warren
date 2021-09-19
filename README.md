# Warren - Stock Price Predictor

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/0293f2ebda4c48ce9cbb0805d9fda2be)](https://www.codacy.com/gh/nityansuman/warren/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nityansuman/warren&amp;utm_campaign=Badge_Grade)
![GitHub](https://img.shields.io/github/license/nityansuman/warren)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/nityansuman/warren)
![GitHub repo size](https://img.shields.io/github/repo-size/nityansuman/warren)
![GitHub language count](https://img.shields.io/github/languages/count/nityansuman/warren)
![GitHub last commit](https://img.shields.io/github.com/AmitDark/Warren.gitwarren)

Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price information.

We make use of Facebook's Time Series forcasting algorithm Prophet to predict stock market price of US based companies in real time using multi-variate, single step forecasting strategy.

![Header](src/static/images/main_page.png)

## Getting Started

Download or clone project from github:
```
$ git clone https://github.com/AmitDark/Warren.git
```

Create a project environment (Anaconda recommended):
```
$ conda create --name envname python
$ conda activate envname
```

Install prerequisites:
```
$ pip install -r REQUIREMENTS.txt
```

Run project:
```
$ cd warren
$ python runserver.py
```

## Model Validation Analysis

**Facebook (Stock: FB) Validation**
![FB_validation](src/static/images/fb_forecast_30_day_validation.png)

**Microsoft (Stock: MSFT) Validation**
![MSFT_validation](src/static/images/msft_forecast_30day_validation.png)

**Google (Stock: GOOGL) Validation**
![GOOGLE_validation](src/static/images/googl_forecast_30day_validation.png)

## Support

If you like the work I do, show your appreciation by 'FORK', 'STAR' and 'SHARE'.

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
