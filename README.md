## Crude Oil Price Prediction Using Neural Network

This project aims to predict the price of crude oil based on historical data using a neural network. The dataset used contains the date, price, percentage change, and other relevant information about crude oil.
link of data: [Kaggle](https://www.kaggle.com/datasets/sc231997/crude-oil-price?select=crude-oil-price.csv)

### Steps Taken

1. **Data Preprocessing**: 
   - Converted the date column to datetime format.
   - Checked and removed any null values.
   - Removed duplicate rows.
   - Visualized the trend of crude oil prices over time.

2. **Exploratory Data Analysis (EDA)**:
   - Calculated and visualized the average percentage change and average change by year.
   - Plotted a time series graph to understand the price trend over time.

3. **Feature Engineering**:
   - Extracted the year from the date column.
   - Converted the date column to a numerical value representing days since a reference date.
   - Split the data into independent and dependent variables, and performed feature scaling.

4. **Neural Network Modeling**:
   - Built a neural network using TensorFlow and Keras.
   - Defined the structure of the neural network with multiple layers.
   - Compiled the model using an Adam optimizer and mean squared error as the loss function.
   - Trained the model on the training data for 1000 epochs.

5. **Model Evaluation**:
   - Evaluated the model on the test data to calculate the loss and mean absolute error.
   - Made predictions using the test data and compared them with actual values.

### Results

The trained neural network was able to predict crude oil prices based on historical data. The model achieved a certain level of accuracy and can be further fine-tuned for better performance.

## Contact

- LinkedIn: [Jorge Chaves Montiel](https://www.linkedin.com/in/jorge-chaves-montiel/)
- Email: jchavezmontiel@gmail.com

Thanks for reviewing my project! I am excited to explore new opportunities in the world of data analytics, finance, machine learning and deep learning. Feel free to contact me for more information about my work! 📊📈💼
