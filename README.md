# Sales Forecasting

One of the planning usecases to figure out what could be the potential sales and revenue opportunity coming out of the
    new business models. 
    Current usecase is analysing IBM dataset to predict Win or Loss of a deal and also calculating probability of winning.
    Steps covered :<br>
    1.	Read excel file and perform Exploratory Data Analysis (EDA) to know the relationship between features and response values.<br>
    2.  Clean and prepare the data<br>
        a.	Convert categorical data into numerics<br>
        b.  Check for correlation between features and remove unwanted/highly correlated features from dataset.<br>
    3.  Perform Feature Selection techniqu like - Dimensionality Reduction technique to get the desired features.<br>
        a. Apply Principal Component Analysis technique <br>
    5.  Predicting win or loss using classification-<br>
        a.  Split the dataset into test data and training data<br>
        b.  Train model using diff classification algorithms<br>
        c.  Get Accuracy of each model<br>
    6.	Treating the same model for regression and predicting probability of win. Here since the <br>
        training data will have 0/1 as Win/Loss, model will regress between 0 and 1 and giving us probability<br>
        a.  Split the dataset into test data and training data<br>
        b.  Train model using diff regression algorithms<br>
        c.  Get Accuracy of each model(used 50% as a threshold value for difference between actual and predicted value)<br>
        d.	Cap the predicted probability values to be between 5% to 90%.<br>
