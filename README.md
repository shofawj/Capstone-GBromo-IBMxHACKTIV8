# Capstone-GBromo-IBMxHACKTIV8

## Gunung Bromo Visitor Sentiment Analysis Project using IBM Granite LLM

This project explores how tourists experience Gunung Bromo, one of Indonesia’s most iconic natural destinations, by analyzing publicly available Google Maps reviews using artificial intelligence.

Using IBM Granite — a powerful large language model — this project processes and interprets unstructured reviews to extract:
1. Sentiment (positive/negative/mixed)
2. Common complaints and praises
3. Provide actionable recommendations for tourism management
4. Visualize key trends in visitor feedback

The objective is to generate insights that can improve visitor satisfaction, identify pain points, and support data-driven decision-making in tourism management.

The analysis leverages IBM's Granite-3.3-8b LLM model through Replicate's API to perform sophisticated sentiment analysis and thematic extraction from review texts.

### Dataset
Source: Google Maps Hotel Reviews (self-collected)
Format: .xlsx (Excel spreadsheet)
Access: Loaded directly into Google Colab as a local file

All data processing, visualization, and analysis were done in Python using:
- pandas for data handling
- matplotlib and seaborn for visualization
- Counter and simple NLP for keyword analysis

Analysis Process
- Data Preparation
- LLM Analysis - For each review, the AI identifies:
- Aggregation
  1. Calculate sentiment percentages
  2. Extract frequent themes
  3. Generate visualizations
- Recommendation Engine
  1. Suggest improvements based on findings
  2. Highlight strengths to promote
 
### Example Result
Original Review:
Pemandangan luar biasa indah, perbukitan hijau dan perjalanan ekstrim, lebih baik naik sepeda motor daripada menyewa jeep 👍

AI Analysis:
Sentiment: Positive
Summary: The reviewer expresses awe for the extraordinary view, the green hillscape, and the extreme journey, preferring to ride a motorbike over renting a jeep.
Things Mentioned (Praises): 
- Breathtaking view (pemandangan luar biasa indah)
- Green hillscape (perbukitan hijau)
- Extreme journey (perjalanan ekstrim)
- Preference for motorbike over jeep for transportation

Complaints: None

Praises: The extraordinary view, the lush green hills, the thrilling journey experience
Recommendation: Continue emphasizing the unique and thrilling aspects of the journey to Gunung Bromo, and consider offering motorbike rentals as a standard or preferred option alongside jeep rentals to cater to diverse visitor preferences.


