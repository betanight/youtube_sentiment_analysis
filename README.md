# YouTube Sentiment Analysis

This project explores the relationship between YouTube comment sentiment and engagement metrics like the like/dislike ratio. The goal is to understand how viewers actually feel about videos by analyzing their comments and comparing them to how they interact through likes and dislikes.

We started by labeling sentiment using a basic tool called TextBlob, which looks for positive or negative words. Later, we trained a custom machine learning model to better capture the tone of comments using real patterns in the text. The project includes data exploration, visualizations, and comparisons between sentiment and viewer engagement.

---

## 📁 Project Structure

- `notebooks/` – Step-by-step Jupyter notebooks showing analysis, sentiment labeling, and modeling.
- `datasets/` – Contains the full YouTube dataset (`USvideos.csv`, `UScomments.csv`). These files are too large to preview on GitHub, but they load fine locally.
- `requirements.txt` – List of Python packages used in the project.

---

## 🛠️ Setup Instructions (Mac/Linux/Windows)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/youtube_sentiment_analysis.git
cd youtube_sentiment_analysis
```

### 2. Create and activate a virtual environment

**Mac/Linux:**

```bash
python3 -m venv sentiment_venv
source sentiment_venv/bin/activate
```

**Windows:**

```bash
python -m venv sentiment_venv
.\sentiment_venv\Scripts\activate
```

### 3. Install required dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook (optional)

```bash
jupyter notebook
```

---

## 🔍 What We’ve Found So Far

Throughout the project, we compared how viewers engage with a video through likes/dislikes versus how they express their opinions in the comments. Using TextBlob and a custom-trained sentiment model, we analyzed thousands of YouTube comments and matched them with engagement metrics.

Here are a few things we've discovered:

- Videos can have **perfect like/dislike ratios** but **entirely negative comment sentiment**, showing a clear disconnect between public engagement and written feedback.
- Many viewers are more likely to **comment their thoughts** than to leave a dislike. Dislikes are underused, while negative feedback often shows up in comments.
- The **TextBlob** model provided a solid starting point, but our **trained model** captured sentiment much more accurately, especially in informal or sarcastic comments.
- We found that the correlation between like/dislike ratio and comment sentiment is **weak (around 0.28)**, meaning public engagement and viewer opinion often tell **different stories**.
- Visualizations like scatterplots helped identify outlier videos where the numbers don’t match the tone, highlighting interesting case studies for further review.

These findings suggest that sentiment analysis offers a deeper look into how people really feel about content — far beyond just likes and views.
