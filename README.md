```markdown
**YouTube Sentiment Analysis**

This project explores the relationship between YouTube comment sentiment and engagement metrics like the like/dislike ratio. The goal is to understand how viewers actually feel about videos by analyzing their comments and comparing them to how they interact through likes and dislikes.

We started by labeling sentiment using a basic tool called TextBlob, which looks for positive or negative words. Later, we trained a custom machine learning model to better capture the tone of comments using real patterns in the text. The project includes data exploration, visualizations, and comparisons between sentiment and viewer engagement.

---

**📁 Project Structure**

- `notebooks/` – Step-by-step Jupyter notebooks showing analysis, sentiment labeling, and modeling.
- `datasets/` – Contains the full YouTube dataset (`USvideos.csv`, `UScomments.csv`). These files are too large to preview on GitHub, but they load fine locally.
- `requirements.txt` – List of Python packages used in the project.

---

**🛠️ Setup Instructions (Mac/Linux/Windows)**

**1. Clone the repository**
```bash
git clone https://github.com/your-username/youtube_sentiment_analysis.git
cd youtube_sentiment_analysis
```

**2. Create and activate a virtual environment**

*Mac/Linux:*
```bash
python3 -m venv sentiment_venv
source sentiment_venv/bin/activate
```

*Windows:*
```bash
python -m venv sentiment_venv
.\sentiment_venv\Scripts\activate
```

**3. Install required dependencies**
```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook (optional)**
```bash
jupyter notebook
```

---

**🚀 How to Explore or Contribute**

If you're interested in working on this project:
- Open any notebook in the `notebooks/` folder to follow the full workflow
- Explore the dataset and visualizations to gain insights
- Improve the sentiment model or experiment with new techniques
- Add new videos or comments to test model predictions
- Fork the repository or open a pull request with new ideas or features

This project is collaborative and open to contributions from others.

---

**📦 Dataset Info**

- Original dataset source (Kaggle): https://www.kaggle.com/datasnaek/youtube
- Files include `USvideos.csv` and `UScomments.csv`
- These files are stored locally in the `datasets/` folder and are too large to view directly on GitHub
- You can open them using Python (e.g. `pandas.read_csv()`) or any text editor
```