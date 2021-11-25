# Spotify Hit Prediction
## 1. EDA
<img width="668" alt="image" src="https://user-images.githubusercontent.com/12545194/143507183-8b0ba7ac-3973-4571-8822-8e0602850319.png">
<img width="677" alt="image" src="https://user-images.githubusercontent.com/12545194/143507222-8d7e9778-8c6b-4ebc-88cf-80a9964a2aa2.png">

## 2. Data Preprocessing
### 2.1 Removing Outliers
<img width="680" alt="image" src="https://user-images.githubusercontent.com/12545194/143507304-b6973750-daed-4db9-99d1-a65075c074e9.png">

### 2.2 VIF Analysis on correlated features
<img width="578" alt="image" src="https://user-images.githubusercontent.com/12545194/143507324-3af109b4-7187-487e-93cb-faf0fdfc1f94.png">

### 2.3 Drop columns that are not needed
- “Energy” feature was dropped from the complete dataset based on high VIF score
- Uninformative columns were dropped - “Uri”, “Track”, “Artist”

## 3. Performance of models
<img width="691" alt="image" src="https://user-images.githubusercontent.com/12545194/143507069-043e5e39-7107-4b61-bf42-ce77c924cebe.png">

## 4. Feature Importance
<img width="669" alt="image" src="https://user-images.githubusercontent.com/12545194/143507530-de621e13-72f1-46d9-92c5-b1367a5cc9b8.png">

## 5. Insights
Top features from variable importance and exploratory data analysis match. The combined insight is:

All Tracks that are hits are :
- More on Vocals
- More danceable 
- Louder

## 6. Recommendations
- Artist should go tweak their songs to increase their chances of creating a “hit” song
- Business Case: deciding singles for an album release
