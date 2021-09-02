
<h1>Digit Recognition Classification model</h1>
<ul><h3>Steps to create classification model</h3>
  <li>Load the Dataset</li>
  <li>Perform image preprocessing</li>
  <li> Create A CNN Model</li>
  <li>test the model</li>
  <li>Evaluate the model</li>
</ul>
<br>
<h2>Load the Dataset</h2>
<p>first step is load the dataset with the help of pandas library, <b>read_csv</b> is used to import csv, excel and more format dataset, in this model creation we have used <b>mnist </b> dataset  have used which have 50k training and 10k have testing data of digit from 0-9.</p>
<br>
<h2>Image Preprocesing
</h2>
<p> Before giving image as input, we have to preprocess it. Because model would not take image as input, before giving image as input we have to change into array of float type data with preprosessing in-build function or library.  </p>
<h2>Create A CNN Model</h2>
<p>Create a CNN model with keras library which is available in tensorflow library. To add convnet layer con2D function is used. provide the required parameter and compile/fit the model.</p>
<h2>Test the Model </h2>
<p>After creation of model test the model with test data and check your accuracy.</p>
<h2>Evaluate the Model</h2>
<p>After completed all the above point now time to evaluate the model with either python tkinter widget or Flask/Django framework  </p>
<h3>Thank you! </h3>
