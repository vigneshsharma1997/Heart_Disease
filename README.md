# Heart_Disease
Neural_Networks
<!DOCTYPE html>
<html>
<body>
  <h1>Objective</h1>
  <p>This project will focus on predicting heart disease using neural networks. Based on attributes such as blood pressure, cholesterol levels, heart rate, and other characteristic attributes, patients will be classified according to varying degrees of coronary artery disease. This project will utilize a dataset of 303 patients distributed by the UCI Machine Learning Repository.</p>
  <p>Machine learning and artificial intelligence are going to have a dramatic impact on the health field. Familiarizing yourself with the data processing techniques appropriate for numerical health data and the most widely used algorithms for classification tasks is an incredibly valuable use of your time!</p>

  <h2>Things to do:</h2>
  <ol>
    <li>Read the <code>heart.csv</code> data, clean the data, and normalize the features.</li>
    <li>Split the data into train and test sets.</li>
    <li>Use the <code>Keras</code> package to build the model. The code to build such a model is provided below:</li>
  </ol>
  <pre><code>
    import keras
    from keras.models import Sequential
    from keras.layers import Dense

    # Define the model
    model = Sequential()
    model.add(Dense(64, activation='relu', input_dim=num_features))
    model.add(Dense(64, activation='relu'))
    model.add(Dense(1, activation='sigmoid'))

    # Compile the model
    model.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])
  </code></pre>
  <li>Evaluate the model across various metrics.</li>
</body>
</html>
