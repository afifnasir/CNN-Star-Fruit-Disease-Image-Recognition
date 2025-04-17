# 🍈 Starfruit Condition Prediction using CNN

This project leverages Convolutional Neural Networks (CNNs) to classify starfruits as either **healthy** or **unhealthy** based on their images. It uses deep learning techniques to detect visual defects in fruits and provides an automated solution for fruit quality inspection.

---

## 📚 Features

- **Binary Classification**: 
  - **Healthy**: Starfruits in good condition.
  - **Unhealthy**: Starfruits with visible defects.
- **Image Preprocessing**: Handles resizing and normalization of input images.
- **Trained CNN Model**: Achieves high accuracy in distinguishing fruit conditions.
- **User-Friendly Visualization**: Displays input images alongside prediction results.

---

## 🗂️ Dataset

The dataset contains two categories of images:
- **Healthy Fruits**: Starfruits in their natural, fresh state.
- **Unhealthy Fruits**: Starfruits with defects or deterioration.

Sample images are included for reference.

---

## 🧠 Model Workflow

1. **Input**: An image of a starfruit.
2. **Preprocessing**: 
   - Resized to the required dimensions.
   - Normalized for better model performance.
3. **Prediction**: The trained CNN model classifies the fruit as:
   - `Healthy Fruit`
   - `Unhealthy Fruit`
4. **Output**: The condition is displayed along with a confidence score.

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- Required Python libraries:
  - TensorFlow
  - Keras
  - NumPy
  - Matplotlib

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/starfruit-condition-prediction.git
   cd starfruit-condition-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook to explore and run the code:
   ```bash
   jupyter notebook Starfruit-Good-Bad Condition Prediction.ipynb
   ```

---

## 🚀 How to Use

1. Place the fruit image you want to classify in the appropriate directory.
2. Use the provided code to preprocess and classify the image:

   ```python
   image_path = 'path_to_image/unhealthy_fruit.png'
   processed_image = load_and_show_image(image_path)

   # Make a prediction
   prediction = model.predict(processed_image)

   # Interpret the result
   if prediction > 0.5:
       result = "Unhealthy Fruit"
   else:
       result = "Healthy Fruit"

   print("Prediction:", prediction, result)
   ```

3. View the results and classification output.

---

## 📊 Example Predictions

### Healthy Fruit
![Healthy Example](path/to/healthy_image.jpg)

### Unhealthy Fruit
![Unhealthy Example](path/to/unhealthy_image.png)

---

## 💻 File Structure

- **Dataset**: Contains images of healthy and unhealthy starfruits.
- **Preprocessing**: Scripts for resizing and normalizing images.
- **Model**: Includes the trained CNN model.
- **Notebook**: Jupyter Notebook for demonstration and experimentation.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas to improve this project or want to add new features, feel free to:
- Fork the repository.
- Make your changes.
- Submit a pull request.

---

## 📝 License

This project is licensed under the MIT License. Feel free to use and modify it as needed. See the LICENSE file for details.


