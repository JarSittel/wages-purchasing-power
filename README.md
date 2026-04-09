Wages vs. Inflation - Purchasing Power Forecast

I built this project around a simple but troubling question: if inflation keeps outpacing wages, what does that actually look like 20 years from now?
I constructed a ratio of median household income to the Consumer Price Index using data from the U.S. Census Bureau and the Federal Reserve (FRED), spanning 45 years of historical data from 1980 to 2025. I then trained an LSTM encoder-decoder neural network to forecast how that ratio evolves over time. The model predicted a 12-13% loss in real purchasing power by 2045.
The findings were written with policymakers and the Federal Reserve as the intended audience. It's the kind of project I'm drawn to because the implications are real. This affects how people plan their finances, how the government thinks about wage policy, and what the next generation can expect from the economy.
Results

Forecasted ~13% decline in real purchasing power by 2045
Sub-1% training loss (MSE) across most epochs
45 years of historical data used for training (1980–2025)
20-year forecast horizon

Tools
Python, TensorFlow, Keras, pandas, NumPy, scikit-learn, matplotlib, FRED Data, U.S. Census Bureau
