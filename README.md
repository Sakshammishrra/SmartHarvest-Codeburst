Here's the updated README file with the demo video link included:

---

# SmartHarvest

Welcome to **SmartHarvest**! This project is part of our participation in the AI/ML Healthcare Hackathon. It's a proof-of-concept (POC) that showcases how machine learning (ML) and deep learning (DL) can be leveraged in precision farming. 

**DISCLAIMER ⚠️**  
This project is for demonstration purposes only. The data used comes with no guarantee, and we do not recommend using it for actual farming decisions. The creator is not responsible for any outcomes from such use. The project highlights the potential of ML/DL in precision farming when developed on a larger scale with authentic and verified data.

## Motivation 💪

Agriculture is a critical sector for the economic growth of many countries, including India. With a significant portion of the population relying on agriculture for their livelihood, integrating advanced technologies like ML and DL can help farmers improve and maximize their yield.

## Applications

SmartHarvest comprises three main applications:

1. **Crop Recommendation**
   - Users can input soil data to get predictions on the best crops to grow.

2. **Fertilizer Recommendation**
   - Users can provide soil data and the type of crop they are growing. The application will suggest necessary nutrient adjustments and recommend appropriate fertilizers.

3. **Plant Disease Prediction**
   - Users can upload an image of a diseased plant leaf. The application identifies the disease and provides information on its cause and prevention.

## Data Sources 📊

- **Crop Recommendation Dataset** (custom-built)
- **Fertilizer Suggestion Dataset** (custom-built)
- **Disease Detection Dataset**

## Notebooks 📓

The corresponding code is available on Kaggle Notebooks:

- [Crop Recommendation](#)
- [Disease Detection](#)

## Built With 🛠️

- [Heroku](https://heroku.com/) for deployment
- [Git](https://git-scm.com/) for version control
- [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) for environment management

## Deployment 🚀

The website is deployed on Heroku and can be accessed [here](#). Note: The website might take a minute to load as the server could be in hibernate state.

## How to Use 💻

### Crop Recommendation System
- Enter the nutrient values of your soil, state, and city.
- Ensure N-P-K values are the ratios between them.
- Use common city names for accurate weather data retrieval.

### Fertilizer Suggestion System
- Input the nutrient contents of your soil and the crop you want to grow.
- The algorithm will suggest nutrient adjustments and recommend fertilizers.

### Disease Detection System
- Upload an image of the plant leaf.
- The algorithm identifies the crop type, checks for diseases, and provides recommendations.

## Supported Crops

Currently, the system supports limited crop types. 

## Running Locally 🛠️

### Prerequisites
- Ensure you have Git and Anaconda or Miniconda installed.

### Steps
1. Clone the project:
    ```sh
    git clone https://github.com/Gladiator07/Harvestify.git
    ```
    For the updated deployment code:
    ```sh
    git clone -b deploy https://github.com/Gladiator07/Harvestify.git
    ```

2. Create and activate the conda environment:
    ```sh
    conda create -n harvestify python=3.6.12
    conda activate harvestify
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the application:
    ```sh
    python app.py
    ```

5. Open the provided localhost URL in your web browser.

### Full Demo Video
[SmartHarvest Demo Video](https://drive.google.com/file/d/1ZzdHS09TXE8UBsswoW0S_PjCNmbtYJ_K/view?usp=drive_link)

## Contribute 👨‍💻

Read [CONTRIBUTING.md](#) for details on our code of conduct and how to submit pull requests.

## Usage ⚙️

Feel free to develop further and add your work to this project. Please credit the original source and include the link to this repo in your reports.

## Further Improvements 📈

- Improve the CSS code for better structure.
- Enhance the frontend design.
- Collect more data via web scraping for accuracy.
- Gather additional plant images to enhance disease detection robustness.
- Write modularized code instead of Jupyter Notebooks.

## Team Codeburst

- Saksham Mishra
- Ravi Kumawat
- Singh Mohit Manoj
- Dharmendra Vaghela

---
