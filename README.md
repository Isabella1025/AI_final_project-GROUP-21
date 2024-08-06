Link to youtube video:										
https://youtu.be/0Kgnkd9Rlbo

Link to the google drive with the model and the tokenizers:
https://drive.google.com/drive/folders/1NJAURrcoZ5rw_So78wPSl1dEzQo5wDx?usp=drive_link 

Link to deployed app
https://huggingface.co/spaces/Isabella1025/AI_final-group17


# Product Review Rating Predictor

Welcome to the **Product Review Rating Predictor**! This application uses a fine-tuned BERT model to predict ratings for product reviews. The ratings are predicted on a scale from 1 to 5 based on the sentiment of the review text.

## Features

- **Sentiment Analysis**: Predict the rating of a product review.
- **User-Friendly Interface**: Easy-to-use text input for review prediction.
- **Real-time Prediction**: Get instant predictions for your product reviews.

## Getting Started

### Prerequisites

- Python 3.7+
- Streamlit
- Transformers
- PyTorch
- Safetensors
- Ngrok

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/product-review-rating-predictor.git
    cd product-review-rating-predictor
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Download and save the model:**

    - Ensure you have saved your fine-tuned BERT model and tokenizer files in a directory, e.g., `AI_FINAL_PROJECT`.

4. **Set up Ngrok:**

    - Sign up on [Ngrok](https://dashboard.ngrok.com/signup) to get your authentication token.
    - Replace `YOUR_NGROK_AUTH_TOKEN` in the code with your actual Ngrok token.

### Running the Application

1. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

2. **Expose the app using Ngrok:**

    In the same directory, run the following command:

    ```bash
    ngrok http 8501
    ```
    - Copy the public URL generated by Ngrok and open it in your browser.



