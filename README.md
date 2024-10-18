# Dog Breed Identification 🐕📷

![image_50403841](https://github.com/user-attachments/assets/7d8e72d1-81a0-4141-aee3-a7a90b1ed316)
![image_123650291 (3)](https://github.com/user-attachments/assets/7622d471-2eb8-4598-9d02-abda0fc1026b)

https://github.com/user-attachments/assets/901e3c81-7a84-4998-b6ab-8cfc03ea0633


## Overview
The **Dog Breed Identification** project integrates Django with Convolutional Neural Networks (CNNs) to develop a web application that can accurately predict a dog's breed from an uploaded image. This tool aims to assist pet owners, veterinarians, shelters, and dog buyers in identifying dog breeds quickly and accurately.

**Watch the demo video here: [https://www.linkedin.com/posts/tobiloba-oluwadamilare-a850b0223_convolutionalneuralnetworks-tensorflow-django-ugcPost-7237024131546828800-9wrR?utm_source=share&utm_medium=member_desktop]**

---

## Project Goals
- **Accurate Breed Prediction**: A deep learning model that can predict the breed of a dog from an image, trained on a dataset containing 8 different dog breeds.
- **Buyer Verification Tool**: Helps dog buyers verify if a dog's breed matches a seller's claim, aiding in informed purchasing decisions.
- **User-Friendly Interface**: Built with Django, the web app provides an intuitive platform for users to upload images and receive predictions in real-time.
- **Seamless Integration**: The CNN model is fully integrated into the Django application, providing immediate predictions with a smooth user experience.

---

## Methodology
1. **Data Collection & Preprocessing**:  
   - A dataset of images from 8 distinct dog breeds was collected.
   - Images were preprocessed via resizing, normalization, and data augmentation to enhance model performance.

2. **Model Architecture**:  
   - A CNN with multiple convolutional, pooling, and fully connected layers was used to effectively classify the breeds.
   - Techniques such as early stopping and learning rate scheduling were applied to improve accuracy.

3. **Training & Evaluation**:  
   - The model was rigorously trained and evaluated to ensure high accuracy, precision, and recall.

4. **Django Deployment**:  
   - The model was deployed into a Django web app where users can upload images and instantly receive breed predictions.

---

## Outcomes & Future Development
- The application successfully integrates deep learning and web development, providing an accurate and user-friendly breed identification tool.
- Future plans include:
  - Expanding the dataset to cover more dog breeds.
  - Adding detailed breed information, including origin, temperament, and pros/cons of ownership, to assist users in learning more about different breeds.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/tobibiggest/dog-breed-identification.git
   ```

2. Navigate to the project directory and install dependencies:
   ```bash
   cd dog-breed-identification
   pip install -r requirements.txt
   ```

3. Run migrations:
   ```bash
   python manage.py migrate
   ```

4. Start the Django server:
   ```bash
   python manage.py runserver
   ```

5. Open the web application in your browser at `http://127.0.0.1:8000` and upload an image to identify the dog's breed.

---

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
