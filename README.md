# Capstone-GBromo-IBMxHACKTIV8

## Tourist Sentiment and Experience at Gunung Bromo from Google Maps Reviews Using IBM Granite LLM

This project explores how tourists experience Gunung Bromo, one of Indonesia’s most iconic natural destinations, by analyzing publicly available Google Maps reviews using artificial intelligence.

Using IBM Granite — a powerful large language model — this project processes and interprets unstructured reviews to extract:
1. Sentiment (positive/negative/mixed)
2. Common complaints and praises
3. Key aspects mentioned (e.g., view, access, pricing, facilities)
4. Actionable recommendations for tourism authorities and local businesses

The objective is to generate insights that can improve visitor satisfaction, identify pain points, and support data-driven decision-making in tourism management.

### Raw Dataset
Source: Google Maps Hotel Reviews (self-collected or provided)
Format: .xlsx (Excel spreadsheet)
Access: Loaded directly into Google Colab as a local file

The reviews (from Google Maps) were processed in .xlsx format and loaded into Python with pandas. Each review was sent to IBM Granite with a prompt instructing the model to return a structured analysis. The outputs were saved and analyzed in aggregate to uncover patterns and trends.

All data processing, visualization, and analysis were done in Python using:
- pandas for data handling
- matplotlib and seaborn for visualization
- Counter and simple NLP for keyword analysis


