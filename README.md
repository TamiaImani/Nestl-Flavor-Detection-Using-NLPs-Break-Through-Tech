# Nestle-Flavor-Detection-Using-NLPs-Break-Through-Tech
Project Description
    Purpose:
This project uses AI and big data to uncover consumer flavor preferences for healthy, anti-aging snacks. By analyzing Amazon reviews, we aim to identify key flavor trends and generate innovative product ideas.

Project Overview, Objectives, and Goals:
    Overview: Leveraging NLP and machine learning techniques to process consumer reviews for insight into preferences and trends in healthy snack flavors.
Objectives:
Extract key flavor themes and patterns from textual data.
Generate actionable product ideas to inform Nestlé’s R&D efforts.
Provide insights for targeted marketing strategies.
Importance: As consumer preferences shift toward healthy and clean eating, understanding these trends supports product innovation in the health snack market.

Methodology:
    Data Collection: Sourced from the 2023 Amazon Reviews dataset (McAuley Lab on Hugging Face), focused on the Grocery and Gourmet Food category.
  Data Preprocessing:
Cleaned, filtered, and standardized text data.
Applied stemming/lemmatization and removed duplicates and irrelevant records.

Modeling:
    Utilized Latent Dirichlet Allocation (LDA) for topic modeling.
Highlighted relevant keywords and patterns for analysis.
Generative AI: Used outputs from LDA to prompt ChatGPT for creative product generation.
Results and Key Findings:
Performance Metrics: LDA effectively identified key flavor-related topics.
Insights: Topics revealed consumer preferences for flavors like organic fruits, protein snacks, and low-sugar options.
Generated Products: Innovative product ideas, such as Protein-Packed Matcha Energy Bars, were created using GenAI.

Visualizations:
    Word Clouds: Visualized key topics and keywords.
  Topic Outputs: Weighted importance of terms within categories (e.g., fruits, protein, low carb).
Potential Next Steps:
Expand data collection to include additional categories like Health & Personal Care.
Enhance the topic detection algorithm to analyze both high and low ratings.
Test the approach on internal Nestlé product development initiatives.

Table of Contents
Project Title and Description
Installation
Usage
Contributing
License
Credits and Acknowledgments
Installation
Prerequisites:
Python 3.8 or higher
Libraries: pandas, NumPy, scikit-learn, matplotlib, NLTK, gensim, ChatGPT API access

Steps:

Clone the repository:

bash

Copy code

git clone https://github.com/your-username/nestle-flavor-detection.git

Install dependencies:

bash

Copy code

pip install -r requirements.txt

Download the dataset from Hugging Face and save it in the data/ directory.
Usage
Running the Project:
Prepare Data:
bash
Copy code
python data_preparation.py
Run LDA Model:
bash
Copy code
python lda_model.py
Generate Products with GenAI:
bash
Copy code
python product_generator.py

Example Outputs:
LDA Topics: Keywords such as “fruit,” “organic,” “protein,” and “healthy.”
Generated Products:
Protein-Packed Matcha Energy Bars
Exotic Tropical Fruit Jerky
Contributing
We welcome contributions to improve the project!

Fork the repository.
Create a branch: git checkout -b feature-name.
Submit a pull request detailing your updates.
License
This project is licensed under the MIT License.

Credits and Acknowledgments
  
    Team Members:
Rosemarie Nasta (Hofstra University)
Tamia Thomas (Kennesaw State University)
Michelle Cao (Dickinson College)
Nasrin Ali (George Mason University)
   
    Advisors:
Yi Tong: AI Studio TA (Cornell University)
Mingtao Wu: Nestlé IT NA Innovation Manager
Varun Sriram: Nestlé IT NA Expert Applications Development
Special Thanks: Nestlé and Cornell Break Through Tech AI Studio for their guidance and support.

