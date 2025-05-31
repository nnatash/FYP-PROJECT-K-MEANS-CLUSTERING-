# ARTWORK IMAGE COLOUR DOMINANT SORTER USING K-MEANS CLUSTERING

The project focuses on the significance of image and colour theme in understanding 
visual perception and the representation of colours in digital images. By investigating colour themes extracted from art collections, this project aims to explore the potential of utilizing these palettes for image analysis and dominant colour sorting. 

## Project Objectives
- Identify criteria for evaluating the **usability and distinguishability** of generated colour palettes.
- Develop a **Machine Learning (ML)** model using K-Means to reduce **human subjectivity and error**.
- Create a working **prototype** that extracts and presents dominant colours from artwork images.

## Problem Statement
- Identify criteria for evaluating the **usability and distinguishability** of generated colour palettes.
- Develop a **Machine Learning (ML)** model using K-Means to reduce **human subjectivity and error**.
- Create a working **prototype** that extracts and presents dominant colours from artwork images.

## Methodology
**Data Collection:**
- Image sourced from Kaggle dataset containing 9000 artwork images from various artists [https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time]
  
**Pre-Processing:**
  - Image resizing (400x400), pixel normalization

**Modeling:**
- Applied K-Means Clustering with evaluation using **Elbow** and **Silhouette** methods

**Prototype Development:**
- Built using **Streamlit** for interactive image upload and palette display

**Testing & Evaluation:**
- Compared clustering results at different `k` values (4 vs 5) 

## Results Summary

- **Optimal K = 5** based on Silhouette Analysis, providing richer and more accurate colour palettes.
- Users can upload artwork images and view the **dominant colours** with **percentage distributions**.
- The prototype enables intuitive use for both novice and expert designers.

## Prototype Interface

- Built with **Streamlit** for an easy-to-use web interface.
- Displays uploaded image and the **top 5 dominant colours** extracted via clustering.
- Includes **percentage breakdowns** of each colour for better composition analysis.

## Techniques Used

- **K-Means Clustering**
- **Elbow Method** (WCSS)
- **Silhouette Score**
- **Python**, **OpenCV**, **Matplotlib**, **Streamlit**

## Evaluation

- **K=5** provided better segmentation granularity than K=4.
- Prototype tested on various artwork styles, showing consistent clustering performance.
- Results validated using both **quantitative analysis** and **visual output** inspection.

## Significance

- Reduces manual effort in identifying dominant colours.
- Helps artists/designers make colour-based decisions with **objectivity**.
- Enhances creative workflow and **minimizes human bias** in colour selection.

## 📄 License

This project is intended for academic and educational purposes only.
