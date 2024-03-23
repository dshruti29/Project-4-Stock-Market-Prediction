<a name="readme-top"></a>
<!-- PROJECT 4 README -->

<!-- SAVE THESE NICE PARTS FOR WHEN THE REPO IS PUBLIC
***[![Contributors][contributors-shield]][contributors-url]
***[![Forks][forks-shield]][forks-url]
***[![Stargazers][stars-shield]][stars-url]
***[![Issues][issues-shield]][issues-url]
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Stock Price Predictor - Final Project</h3>

  <p align="center">
    This is a Stock Price Predictor built as part of the Final Project for the Fall 2023 Data Analytics Boot Camp hosted by Washington University in St. Louis with edX.
    <br />
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About the Stock Price Predictor

The Stock Price Predictor was created after our group wanted to see if we could using historical data and different sets of learning models to predict the 200%+ increase in stock price of Celsius Holdings in the first quarter of 2024. If the model is able to predict an unusual increase in stock prices for this specific stock, there is a possibility it could also predict the increase in stock of other companies as well. 

You will mainly be interacting with the Stock Price Predictor through Python code and Streamlit, an open-source framework designed for visualizing data.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Python][Python.com]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To set up a local copy, follow these straightforward steps as provided in the example.

### Prerequisites


  ```sh
  pip install numpy
  pip install matplotlib
  pip install yfinance
  pip install -U scikit-learn
  pip install pandas
  pip install keras
  pip install streamlit
  ```


<!-- INSTALLATION -->
### Installation

1. Install Python pre-requisites. 
2. Clone the repo
   ```sh
   git clone https://github.com/dshruti29/Project-4-Stock-Market-Prediction.git
   ```
3. Start a Jupyter Notebook session and open the celh_lstm_model.ipynb notebook. 
4. The stock modelling is currently prefilled to model data after Celsius Holdings stock history. Feel free to delete instances of the CELH stock moniter and replace with another stock to model. Run all of the cells and export the Keras model. Make sure the model is saved with a .keras extension.
5. Open the stock_price_predictor.py file in VS code and make sure the exported model file name matches what will be loaded by the script. Check if the interpretor is python(dev). Run the file --> Streamlit run stock_price_predictor.py
6. After loading, your environment should note Streamlit running with a localhost or 127.0.0.1 address.
7. Open your brower and navigate to the localhost address listed in the shell. Input your stock symbol. Review the data. Congratulations! You are interacting with the Stock Price Predictor!

For clarification, the other models used in our development process are included in the repo for project rubric grading purposes. 
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Approach -->
## Approach

1-Linear Regression 

Applications in Stock Market Analysis : 
Predictive Modeling: Linear regression can be used to predict future stock prices based on historical data and other relevant factors.
It can help identify trends in stock prices over time and predict whether they are likely to continue or reverse.
R-squared Score: 0.8420478682059745
![linearregression](https://github.com/dshruti29/Project-4-Stock-Market-Prediction/assets/146403979/1056c37b-3579-4b3d-b070-f7c6009c774e)

2-KNN Classifier 
![KNN](https://github.com/dshruti29/Project-4-Stock-Market-Prediction/assets/146403979/658928e9-bc60-44e4-8f20-bcee03a6f69b)

3-LSTM

Because of the sequential nature of time-series data, we need a way to aggregate this sequence of information. From all the potential techniques, the most intuitive one is MA with the ability to smooth out short-term fluctuations.
For this demonstration exercise, we’ll use the closing prices of Celcius stock (ticker symbol CELH) from the past 5 years (2019-01-01 to till date). Analysis data will be loaded from yfinance , which offers a free API for historical and real-time stock market data. 

For our exercise, we’ll be looking at technical analysis solely and focusing on the Simple MA  techniques to predict stock prices. Additionally, we’ll utilize LSTM (Long Short-Term Memory), a deep learning framework for time-series, to build a predictive model and compare its performance against our technical analysis.
It is an extremely powerful algorithm for time series. It can capture historical trend patterns, and predict future values with high accuracy
Since stock prices prediction is essentially a regression problem, the RMSE (Root Mean Squared Error) will be our current model evaluation metrics. 


Sources
https://neptune.ai/blog/predicting-stock-prices-using-machine-learning
https://www.youtube.com/watch?v=0E_31WqVzCY

The questions to think before investing in this stock 

- Will the Hyper growth continue 
- Competition in the market  


<!-- CONTRIBUTORS -->
## CONTRIBUTORS

* Chris Burk - Developer - [Github](https://github.com/burk992)
* Shruti Deshpande - Developer - [Github](https://github.com/dshruti29)
* Tadeo Espinoza - Developer - [Github](https://github.com/Tadespi)
* Emma Holtgrieve - Developer - [Github](https://github.com/eholtgrieve)



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage 

Trading stocks is notoriously challenging due to market volatility and complexity. However, data modeling and analysis offer a transformative solution. By harnessing advanced algorithms, investors can uncover hidden patterns and trends, enabling more informed decisions. Predictive models based on historical data empower traders to anticipate market movements and manage risks effectively. Embracing data-driven strategies simplifies stock trading, offering greater precision and confidence in navigating the financial markets.

With a simple Python module interactions, the Stock Price Predictor allows beginning traders to visualize and understand historical data and how it could affect future trading of single stocks.

<!-- ETHICAL CONSIDERATIONS -->
## Ethical Considerations 

* Predicting stock market movements entails significant uncertainty and risk, given the volatile nature of financial markets. It's crucial to acknowledge the inherent unpredictability and exercise caution when making trading decisions based on forecasts. Employing diverse models and strategies can help mitigate risks and enhance prediction accuracy.
* The developers of this project are not liable for any financial losses incurred from the use of our code in stock market trading.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Thanks to Instructor Thomas B for direction early in this project.
* Thanks to our peers in the Data Analytics Boot Camp for challenging us and each other!
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template) was used to create this README file. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/prowoody/Project-3.svg?style=for-the-badge
[contributors-url]: https://github.com/Tadespi/Project_4/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/tadespi/Project_4.svg?style=for-the-badge
[forks-url]: https://github.com/Tadespi/Project_4/network/members
[stars-shield]: https://img.shields.io/github/stars/tadespi/Project_4.svg?style=for-the-badge
[stars-url]: https://github.com/Tadespi/Project_4/stargazers
[issues-shield]: https://img.shields.io/github/issues/tadespi/Project_4.svg?style=for-the-badge
[issues-url]: https://github.com/Tadespi/Project_4/issues
[license-shield]: https://img.shields.io/github/license/tadespi/Project_4.svg?style=for-the-badge
[license-url]: https://github.com/Tadespi/Project_4/blob/master/LICENSE.txt
[Python.com]: https://img.shields.io/badge/Python-ffde57?style=for-the-badge&logo=Python&logoColor=white
[Python-url]: https://www.python.org/
[CSS.com]: https://img.shields.io/badge/CSS-563D7C?style=for-the-badge&logo=CSS3&logoColor=white
[CSS-url]: https://www.w3schools.com/css/
[JS.com]: https://img.shields.io/badge/JavaScript-F0DB4F?style=for-the-badge&logo=Javascript&logoColor=black
[JS-url]: https://www.javascript.com/
