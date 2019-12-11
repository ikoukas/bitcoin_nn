# bitcoin_nn
The output files of my Bitcoin price-trend prediction program

# Bitcoin Medium-Term Prediction and Transactions Suggestion using Deep Learning

I've created a Python program that tries to predict the trend of Bitcoin for (it's a parameter) the next 18 days.

The program has many options regarding the method that will be used to make the prediction some of which involve ANNs, CNNs, RNNs and the R forecast library.

There are also many options regarding the input-data used for the prediction like whether to use the volume of the trading to make the prediction.

Using that prediction there's an algorithm (developed through trial and error) that translates the trend prediction into transactions (if any are suggested) with the goal of increasing your investment in the long term.

There's also an algorithm that decides whether the current date (based on past prices) is "suitable" for a prediction, which explains some gaps between predictions that are shown as flat predictions in the included plot images.

This project includes several outputs of the program in the form of plots, which represent experiments run with historical data and show how an initial investment of 100 dollars would progress if we used this program from the end of 2013 till today.

I don't include any code here but I include the outputs so that the community can evaluate them and tell me if they believe that the investment-increase is based on luck, parameter values selected retroactively to make good predictions which will not work in the future or some other reason besides this being a useful program.

The results aren't always consistent but the gain (in Bitcoin) for the experiment run from the end of 2013 till today vary from 1.8x to 6.5x the initially bought Bitcoin, not including the increase of Bitcoin value, which is an increase of Bitcoin investment between 80% and 550%. In other words the investment increased between 80% - 550% more than by HODLing with an average of around 180%.
