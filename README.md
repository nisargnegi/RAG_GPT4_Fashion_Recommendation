# Fashion-RAG

Fashion-RAG is an innovative project that leverages the power of OpenAI's GPT-4, to analyze and provide deep insights into fashion-related data. This project aims to revolutionize the fashion industry by utilizing state-of-the-art AI techniques to understand trends, classify apparel, and predict fashion preferences. Whether you are a fashion enthusiast, a data scientist, or an industry professional, Fashion-RAG offers valuable tools and insights to explore the vast world of fashion data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install the required dependencies, run the following commands:

```bash
pip install openai
pip install tenacity
pip install tqdm
pip install numpy
pip install pandas
pip install tiktoken
pip install typing
```

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Fashion-RAG.git
    cd Fashion-RAG
    ```

2. **Set up OpenAI API key**:
    - Create a `Config.py` file and add your OpenAI API key:
      ```python
      openai_api_key = "your_openai_api_key"
      ```

3. **Run the Jupyter Notebook**:
    - Open the `Fashion-RAG.ipynb` notebook and run all cells to see the analysis.

## Dataset

The dataset used in this project is stored in the `small_data/archive_small_data/styles.csv` file. It contains 44,424 items of clothing with various attributes such as gender, master category, subcategory, article type, base color, season, year, usage, and product display name.

Example of the dataset:
```plaintext
      id gender masterCategory subCategory  articleType baseColour  season  year   usage                             productDisplayName  
0  15970    Men        Apparel     Topwear       Shirts  Navy Blue    Fall  2011.0  Casual               Turtle Check Men Navy Blue Shirt  
1  39386    Men        Apparel  Bottomwear        Jeans       Blue  Summer  2012.0  Casual             Peter England Men Party Blue Jeans  
2  59263  Women    Accessories     Watches      Watches     Silver  Winter  2016.0  Casual                       Titan Women Silver Watch  
3  21379    Men        Apparel  Bottomwear  Track Pants      Black    Fall  2011.0  Casual  Manchester United Men Solid Black Track Pants  
4  53759    Men        Apparel     Topwear      Tshirts       Grey  Summer  2012.0  Casual                          Puma Men Grey T-shirt  
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```
