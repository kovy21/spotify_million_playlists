# Collaborative Filtering for RecSys Challenge 2018

This repository contains an implementation of **Collaborative Filtering** approaches for the **RecSys Challenge 2018**.  
The project was developed by **Peter Kováč** and **Denis Hoxha** as part of the **6059 Applications of Data Science** course at **WU Wien** (SS 2022).

## Overview
The goal of this project is to develop a recommendation system based on the **Million Playlist Dataset** from Spotify.  
The dataset includes one million playlists, and the project focuses on building a collaborative filtering model to predict user preferences.

## Dataset
- **Dataset:** Million Playlist Dataset (Spotify)  
- **Source:** [RecSys Challenge 2018](https://www.recsyschallenge.com/2018/)  
- **Data Volume:** ~1 million playlists  

## Approach
1. **Data Preprocessing**  
   - Load and clean the dataset  
   - Extract relevant features from playlist metadata  

2. **Collaborative Filtering**  
   - User-based and item-based collaborative filtering  
   - Matrix factorization methods (e.g., SVD)  

3. **Evaluation**  
   - Evaluate model performance using standard metrics (e.g., RMSE, Precision@k)  
