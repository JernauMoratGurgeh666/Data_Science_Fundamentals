# Neural Networks – Step-by-Step Checklist 
How to implement neural networks – with TensorFlow and Keras.

# **1** 💻 **Set up Python environment**  
**2do:** Install Python, IPython, Jupyter and key packages on your machine.
- Install Python 3.6 or later 
- Install IPython and Jupyter notebook
- Install key packages: numpy, pandas, matplotlib, scikit-learn, tensorflow, keras
<br>
https://www.python.org/downloads/
<br>
https://ipython.org/install.html
<br>
https://jupyter.org/install

<br>
<br>

# **2** 📁 **Get the data**
**2do:** Download or acquire the dataset you want to work with.
- Find and download relevant datasets for your task
- Put the data files in your project folder
- Load data into numpy arrays or Pandas DataFrames
<br>
https://archive.ics.uci.edu/ml/index.php
<br>
https://www.kaggle.com/datasets
<br>
https://data.gov/

<br>
<br>

# **3** 🔎 **Explore the data**  
**2do:** Understand your data by visualizing and calculating statistics.
- Use Pandas, matplotlib and seaborn to visualize data
- Find correlations, distributions, outliers etc. 
- Identify issues and preprocess if needed
<br>
https://scikit-learn.org/stable/modules/preprocessing.html
<br>
https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html
<br>
https://matplotlib.org/stable/tutorials/introductory/pyplot.html

<br>
<br>

# **4** 📊 **Prepare data for modeling**   
**2do:** Clean and preprocess data for training.
- Encode categorical variables 
- Split data into train/test sets
- Standardize or normalize features
- Oversample/undersample if needed
<br>
https://seaborn.pydata.org/tutorial/relational.html
<br>
https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html
<br>
https://matplotlib.org/stable/gallery/index.html

<br>
<br>

# **5** 🧠 **Build neural network model**
**2do:** Define and compile a neural network for your task.
- Pick network architecture (Dense, Conv2D etc)
- Add layers, nodes, activations, regularization
- Compile with loss function, optimizer, metrics
<br>
https://keras.io/api/models/sequential/
<br>
https://www.tensorflow.org/api_docs/python/tf/keras/Model
<br>
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

<br>
<br>

# **6** ⏱ **Train the model**  
**2do:** Train the neural network on prepared data.
- Train with fit function, epochs, batch size
- Validate with validation_data and callbacks
- Save checkpoints and early stopping 
<br>
https://www.tensorflow.org/api_docs/python/tf/keras/Model#fit
<br>
https://keras.io/api/callbacks/
<br>
https://www.tensorflow.org/guide/keras/train_and_evaluate

<br>
<br>

# **7** 📈 **Evaluate model performance**
**2do:** Assess model performance on test data.
- Evaluate with model.evaluate()
- Plot train/test loss and metrics 
- Check for over/underfitting
<br>
https://scikit-learn.org/stable/modules/model_evaluation.html
<br>
https://www.tensorflow.org/tensorboard/get_started
<br>
https://www.tensorflow.org/api_docs/python/tf/keras/Model#evaluate

<br>
<br>

# **8** 🌱 **Improve model performance**   
**2do:** Try different approaches to improve model performance.
- Get more or better quality data
- Try different architectures, parameters etc
- Tune hyperparameters with grid/random search
<br>
https://scikit-learn.org/stable/modules/grid_search.html
<br>
https://www.tensorflow.org/tensorboard/hyperparameter_tuning_with_hparams
<br>
https://keras.io/api/optimizers/

<br>
<br>

# **9** 🚀 **Use model for predictions**
**2do:** Apply trained model to make predictions on new data.  
- Load saved model
- Preprocess new data 
- Make predictions with model.predict()
- Interpret and present results
<br>
https://www.tensorflow.org/tutorials/structured_data/time_series#multi-step_model
<br>
https://keras.io/api/models/model/#predict-method
<br>
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression.predict

<br>
<br>

# **10** 🗃️ **Save and deploy model**   
**2do:** Persist and deploy model for others to use.
- Serialize model with to_json() and to_yaml()
- Save model weights
- Create API or web app to serve predictions
<br>
https://www.tensorflow.org/tfx/guide/serving
<br>
https://www.tensorflow.org/lite/guide/python
<br>
https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html
<br>
