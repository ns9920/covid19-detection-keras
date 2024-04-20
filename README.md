<div>
    <h1>COVID-19 Detection using Keras</h1>
    <p>This repository contains a machine learning model built with Keras and TensorFlow for detecting COVID-19 from chest X-ray images. The project consists of three main parts:</p>
    <ol>
        <li><strong>Download Sample Data</strong>: The dataset used for training and testing the model can be downloaded from Kaggle. The dataset contains chest X-ray images of COVID-19 positive and negative cases.</li>
        <li><strong>Build the Dataset</strong>: The downloaded dataset needs to be organized and preprocessed to be used for training the model. This involves steps like resizing images, splitting the data into training and testing sets, and performing data augmentation.</li>
        <li><strong>Train the Machine Learning Model</strong>: The preprocessed data is then used to train a deep learning model based on the VGG16 architecture. The model is trained using transfer learning and fine-tuning techniques to achieve high accuracy in detecting COVID-19 cases.</li>
    </ol>
    <h2>Getting Started</h2>
    <p>To get started with this project, follow these steps:</p>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/ns9920/covid19-detection-keras.git</code></pre>
        </li>
        <li>Download the dataset from Kaggle and place it in the <code>dataset</code> directory.</li>
        <li>Build the dataset by running the <code>build_dataset.py</code> script:
            <pre><code>python build_dataset.py</code></pre>
        </li>
        <li>Train the machine learning model by running the <code>train.py</code> script:
            <pre><code>python train.py --dataset dataset</code></pre>
            This will train the model and save it to the <code>covid19.model</code> file. You can also specify the path to save the training plot using the <code>--plot</code> argument.
        </li>
    </ol>
    <h2>Usage</h2>
    <p>After training the model, you can use it to detect COVID-19 cases from new chest X-ray images. You can modify the provided scripts or create new ones to load the trained model and make predictions on new data.</p>
    <h2>Contributing</h2>
    <p>Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.</p>
</div>
