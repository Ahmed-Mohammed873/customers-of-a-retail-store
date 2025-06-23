# customers-of-a-retail-store
This project applies **K-Means clustering** to segment customers of a retail store based on their **purchase behavior**, specifically:

- Annual income (in thousands of dollars)
- Spending score (1 to 100)

The goal is to divide customers into distinct groups for better **marketing strategies**, **targeted promotions**, and **personalized services**.

---

# Project Structure

customer-segmentation
│
├── code.py      # Main clustering code

├── requirements.txt     # Required Python packages

└── README.md        # Project description


---

# Requirements

Install dependencies using:

pip install -r requirements.txt

---

# Dataset

The project uses synthetic data (generated using NumPy) for demonstration purposes.

You can easily replace it with your own data by reading a CSV file using Pandas.

---

# Methodology

Data Preprocessing

Select features: Annual Income, Spending Score

Normalize using StandardScaler

Finding Optimal K

Elbow method to find the ideal number of clusters (k)

Model Training

Apply KMeans with optimal k

Predict and assign cluster labels

Visualization

2D scatter plot to display clusters using Seaborn

---

# Output

Interactive Elbow Plot to decide optimal clusters.

Color-coded cluster plot

# Use Cases

Targeted Marketing Campaigns

Personalized Customer Communication

Customer Lifetime Value Estimation

Loyalty Programs

