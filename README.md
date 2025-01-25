# Food Product Analysis

## Overview
Food Product Analysis is a web-based application built with Streamlit that helps users analyze packaged food products. The application provides insights into the nutrients present in a product and identifies harmful and non-harmful ingredients. Users can visualize this information through interactive pie charts and search/filter functionalities.

## Features
- **Ingredient Analysis**: Identify harmful and safe ingredients in packaged food.
- **Nutritional Insights**: View nutrients present in the product.
- **Interactive Visualizations**: Pie charts to display the proportion of harmful and non-harmful ingredients.
- **Search and Filters**:
  - Search by product name.
  - Filter by category and brand.
  - Select safety criteria (Safe or Potentially Harmful).
- **Random Image Display**: Showcase random product images for visual engagement.
- **User-Friendly UI**: Intuitive and aesthetically pleasing design with custom CSS.

## Technology Stack
- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `matplotlib` for visualizations
  - `scikit-learn` for similarity analysis
  - `TfidfVectorizer` and `cosine_similarity` for text analysis

## How It Works
1. **Load Data**: The application loads a CSV dataset (`yes no data.csv`) containing product details, such as ingredients, category, and brand.
2. **Ingredient Analysis**: Each product is analyzed to classify its ingredients as harmful or non-harmful.
3. **Visualization**: The proportions of harmful and non-harmful ingredients are displayed in pie charts.
4. **Search and Filters**: Users can search for specific products or apply filters by category, brand, and safety level.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/food-product-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd food-product-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    streamlit run app.py
    ```

## Dataset
- Ensure the `yes no data.csv` file is placed in the project directory.
- The dataset should contain columns like:
  - `Product Name`
  - `Category`
  - `Brand`
  - `Ingredients`
  - `Safety Level`

## Usage
1. Launch the application using Streamlit.
2. Search for a product or filter by category and brand from the sidebar.
3. View the nutrient analysis and ingredient safety details in the main panel.
4. Explore visualizations like pie charts for ingredient safety distribution.

## Customization
- **Styling**: The app uses custom CSS for an enhanced user experience. You can modify the CSS in the `app.py` file.
- **Dataset**: Update the `yes no data.csv` file to include new products or categories.

## Acknowledgments
- Thanks to the open-source community for providing the tools and libraries used in this project.


## Contact
For any questions or feedback, feel free to reach out:
- **Email**: infactsap2025@gmail.com
- **GitHub**: [infact-infact](https://github.com/infact-innfact)
