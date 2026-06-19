# spotify-analysis
# 🎵 Spotify Tracks EDA
> Exploratory data analysis of 113,549 Spotify tracks to uncover 
> what separates a hit song from the rest.

## 📌 Questions Explored
- Which genres dominate popularity on Spotify?
- What audio features define a hit song?
- Does energy, danceability, or tempo predict popularity?
- What do the top 100 most popular tracks have in common?
- How does song duration affect streaming performance?

## 🔑 Key Finding
**Instrumentalness is the strongest predictor of low popularity** — 
vocal-driven songs average nearly 3x the popularity score of 
instrumental tracks. Genre context matters more than any 
individual audio feature.

## 🛠️ Tools Used
| Tool | Purpose |
|---|---|
| Python + Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Seaborn | Statistical visualizations, distributions |
| Matplotlib | Plot customization and layout |
| Plotly Express | Interactive genre and scatter charts |

## 📊 Dataset
[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) 
by Maharshi Pandya — 113,549 tracks across 114 genres with 20 audio features.

## 📁 Notebook Structure
1. Data loading & first look
2. Data cleaning (duplicates, nulls)
3. Questions defined upfront
4. Univariate analysis — distributions of key features
5. Genre popularity ranking
6. Energy vs popularity scatter
7. Correlation analysis
8. Top 100 songs feature breakdown
9. Key findings & conclusions

## 🚀 Next Steps
- Build a popularity score predictor using scikit-learn
- Add release year analysis to track how musical trends shift over time
- Compare audio features between explicit and non-explicit track clusters
