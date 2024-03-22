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
    <a href="https://github.com/Tadespi/Project_4"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Tadespi/Project_4/issues">Report Bug</a>
    ·
    <a href="https://github.com/Tadespi/Project_4/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About the Stock Price Predictor

The Stock Price Predictor was created after our group wanted to see if we could using historical data and different sets of learning models to predict the 200%+ increase in stock price of Celsius Holdings in the first quarter of 2024. If the model is able to predict an unusual increase in stock prices for this specific stock, there is a possibility it could also predict the increase in stock of other companies as well. 

You will mainly be interacting with the Stock Price Predictor through Python code and Streamlit, an open-source framework designed for visualizing data.

The Stock Price Predictor was developed by a team of four developers to submit for their final project of the Data Analytics Boot Camp hosted by Washington University in St. Louis with edX. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Python][Python.com]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To set up a local copy, follow these straightforward steps as provided in the example.

### Prerequisites

* NumPy
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
   git clone https://github.com/tadespi/Project_4.git
   ```
3. Start a Jupyter Notebook session and open the celh_lstm_model.ipynb notebook. 
4. The stock modelling is currently prefilled to model data after Celsius Holdings stock history. Feel free to delete instances of the CELH stock moniker and replace with another stock to model. Run all of the cells and export the Keras model.
6. Review the stock_price_predictor.py file and make sure the exported model file name matches what will be loaded by the script. Run the stock_price_predictor.py file through your Python environment. After loading, your environment should note Streamlit running with a localhost or 127.0.0.1 address.
7. Open your brower and navigate to the localhost address listed in the shell. Input your stock symbol. Review the data. Congratulations! You are interacting with the Stock Price Predictor!

For clarification, the other models used in our development process are included in the repo for project rubric grading purposes. It is unnecessary to interact with them while using the Stock Price Predictor.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Working demo of modelling platform
- [ ] Future development of modelling and visualization platform


See the [open issues](https://github.com/Tadespi/Project_4/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Currently, we are not accepting contributions to this project. Feedback, however, is **greatly appreciated** and all suggestions will be reviewed carefully. If you have feedback that would make this project better, you can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

This project is still in a private phase. We are still working on our licensing functionality. Please check back at a later date.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

* Chris Burk - Developer - [Github](https://github.com/burk992)
* Shruti Deshpande - Developer - [Github](https://github.com/dshruti29)
* Tadeo Espinoza - Developer - [Github](https://github.com/Tadespi)
* Emma Holtgrieve - Developer - [Github](https://github.com/eholtgrieve)

Project Link: [https://github.com/Tadespi/Project_4](https://github.com/Tadespi/Project_4)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage 

Trading stocks is notoriously challenging due to market volatility and complexity. However, data modeling and analysis offer a transformative solution. By harnessing advanced algorithms, investors can uncover hidden patterns and trends, enabling more informed decisions. Predictive models based on historical data empower traders to anticipate market movements and manage risks effectively. Embracing data-driven strategies simplifies stock trading, offering greater precision and confidence in navigating the financial markets.

With a simple Python module interactions, the Stock Price Predictor allows beginning traders to visualize and understand historical data and how it could affect future trading of single stocks.

<!-- ETHICAL CONSIDERATIONS -->
## Ethical Considerations 

While very lightweight at less than 300 lines of code, the Stock Price Predictor takes into account the ethical considerations of the average user in many ways. 

* Predicting stock market movements entails significant uncertainty and risk, given the volatile nature of financial markets. It's crucial to acknowledge the inherent unpredictability and exercise caution when making trading decisions based on forecasts. Employing diverse models and strategies can help mitigate risks and enhance prediction accuracy.
* The developers of this project are not liable for any financial losses incurred from the use of our code in stock market trading.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Thanks to Instructor Tom for direction early in this project.
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
