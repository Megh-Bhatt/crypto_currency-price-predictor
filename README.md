## Crypto Currency Price Predictor
This code delves into the intriguing world of Bitcoin price prediction, utilizing the power of automated time series forecasting with the autots library. Imagine holding a crystal ball that peers into the future of volatile Bitcoin values – that's essentially what this code attempts to achieve.The journey begins by gathering historical Bitcoin price data for a pre-defined period. Think of it as collecting all the past Bitcoin price movements, like tiny puzzle pieces. Next, the data gets meticulously organized into a structured format, ensuring that forecasting models can readily understand and analyze it.<p>

Here's where the magic happens. autots acts like a wise sorcerer, automatically selecting the most fitting forecasting algorithm from its arsenal. This could involve time-tested techniques like exponential smoothing, ARIMA models, or even modern neural networks. Imagine the sorcerer carefully examining the Bitcoin data, discerning hidden patterns and trends, and then choosing the tool best suited to unravel them.
But there's more to it than just picking the right tool. The chosen algorithm goes through a rigorous training process, using the "Close" price as its target and the "Date" as its guidepost. Think of it as the sorcerer feeding the algorithm historical price movements, teaching it to recognize patterns and relationships within the data.
However, no spell is perfect without fine-tuning. autots, our wise sorcerer, doesn't leave things to chance. It automatically adjusts specific settings known as hyperparameters, fine-tuning the algorithm for optimal performance with the Bitcoin data. This meticulous adjustment ensures the model accurately captures the ever-changing dynamics of Bitcoin prices.<p>

Finally, the moment of truth arrives. Armed with its training and fine-tuning, the model generates predictions for future price movements, peering 30 days into the uncertain future. These forecasts are based on the patterns and trends learned from the past, offering valuable insights into what the Bitcoin market might hold.<p>

#### Highlights
How the data of bitcoin looks, the data is take for last 730 days:
![image](https://github.com/Megh-Bhatt/crypto_currency-price-predictor/assets/98394685/518b7cc0-1c99-426f-a465-d7efca4a8b91)
Plotting of closing price of bitcoin of last 730 days:
![image](https://github.com/Megh-Bhatt/crypto_currency-price-predictor/assets/98394685/81009882-30e4-4be6-9fae-14824cba06dd)
Finally results given by model using AUTOTS library:<br>
![image](https://github.com/Megh-Bhatt/crypto_currency-price-predictor/assets/98394685/7946d950-5890-43b8-953f-465e67f36c0f)

#### Library & Roles:
-pandas: For loading and manipulating financial data.
-yfinance: For downloading Bitcoin price data from Yahoo Finance.
-datetime: For date and time calculations.
-plotly: For creating candlestick charts.
-autots: For automated time series forecasting.

#### How to run code in your local computer
 - Download the repository
 - make a new folder extract the files in it
 - Install necessary packages using pip install -r requirements.txt.
 - After finally downloading the requirements you can run the code and train and experiment with the model

