# R — Customer Segmentation Clustering

Customer segmentation analysis using K-Means clustering in R to identify distinct customer groups based on demographics and spending behavior.

## Project

### Customer Segmentation Clustering

Clustering analysis on customer data to segment customers into meaningful groups for targeted marketing strategies.

**Dataset:** Customer segments data with tab-separated values, sourced from DQLab.

**Features:**
| Feature | Description |
|---------|-------------|
| Jenis Kelamin | Gender (Male / Female) |
| Umur | Age |
| Profesi | Profession |
| Tipe Residen | Residential type |
| Nilai Belanja Setahun | Annual spending value |

**Analysis Steps:**
1. Data loading and exploration
2. Categorical to numeric conversion
3. Normalization (annual spending scaled by 1M)
4. K-Means clustering (k=5, nstart=25)
5. Elbow method to validate optimal k
6. Cluster interpretation and segment naming

**Customer Segments Identified:**
| Cluster | Segment Name |
|---------|-------------|
| 1 | Silver Youth Gals |
| 2 | Diamond Senior Member |
| 3 | Gold Young Professional |
| 4 | Diamond Professional |
| 5 | Silver Mid Professional |

**Visualization:**
- Elbow method plot (SSE vs number of clusters)
- Cluster center analysis

## Tech Stack

- **R** — Programming language
- **ggplot2** — Data visualization

## How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/kandref/R.git
   ```
2. Open the R script in RStudio
3. Run the script — dataset is loaded directly from URL

## Author

**Kurnia Andre Febrian**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kurnia-andre-febrian/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/kandref)
