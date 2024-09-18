<h1>Potato Disease Classification using CNN</h1>

<p>This project uses Convolutional Neural Networks (CNN) to classify various types of potato diseases. The goal is to assist farmers and agronomists in identifying diseases at an early stage, helping to improve crop management and yield. The model is built using TensorFlow and Keras, with high accuracy in classifying potato plant diseases.</p>

<h2>Problem Statement</h2>
<p>To build a robust CNN model that accurately classifies potato plant diseases based on images, helping in the early detection and prevention of crop diseases such as Late Blight, Early Blight, and Potato Virus Y.</p>

<h2>Objective</h2>
<p>The objective is to develop a CNN-based solution that provides timely disease detection, improves crop yield, and reduces the need for manual inspections. The model helps farmers take preventive actions and manage their resources efficiently.</p>

<h2>Dataset</h2>
<p>We used a dataset sourced from <a href="https://www.kaggle.com/code/amankrpandey1/potato-disease-classification">Kaggle</a>, which contains labeled images of healthy and diseased potato leaves.</p>

<h2>Model Architecture</h2>
<ul>
  <li>Convolutional Layers for feature extraction</li>
  <li>MaxPooling Layers for down-sampling</li>
  <li>Fully Connected Layers for classification</li>
  <li>Softmax Layer for output</li>
</ul>

<h2>Training</h2>
<ul>
  <li>Optimizer: Adam</li>
  <li>Loss Function: Sparse Categorical Crossentropy</li>
  <li>Training Epochs: 50</li>
  <li>Validation Accuracy: ~95%</li>
</ul>

<h2>Results</h2>
<p>The model successfully classifies diseases in potato plants with an accuracy of around 95%. The trained model is saved for future use as <code>potatoes.h5</code>.</p>

<h2>Advantages</h2>
<ul>
  <li><b>Early Disease Detection:</b> Helps farmers prevent disease spread.</li>
  <li><b>Automated Monitoring:</b> Reduces manual efforts in large farms.</li>
  <li><b>Scalable:</b> Can be integrated into IoT-based monitoring systems.</li>
</ul>

<h2>Future Scope</h2>
<ul>
  <li>Integrating real-time monitoring with IoT devices.</li>
  <li>Improving dataset variety to cover more disease types and conditions.</li>
  <li>Further optimizing the model for better accuracy and robustness.</li>
</ul>

<h2>How to Run</h2>
<ol>
  <li>Clone the repository:
    <pre>git clone https://github.com/username/potato-disease-classification.git</pre>
  </li>
  <li>Install dependencies:
    <pre>pip install -r requirements.txt</pre>
  </li>
  <li>Run the training script:
    <pre>python train_model.py</pre>
  </li>
  <li>Make predictions:
    <pre>python predict.py --image_path /path/to/image.jpg</pre>
  </li>
</ol>

<h2>References</h2>
<ul>
  <li><a href="https://www.tensorflow.org/tutorials/images/classification">TensorFlow Image Classification Tutorial</a></li>
  <li><a href="https://potatoes.ahdb.org.uk/knowledge-library/potato-disease-identification">Potato Disease Identification</a></li>
</ul>
