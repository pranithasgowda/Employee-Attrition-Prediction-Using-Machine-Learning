# Python Data Analysis Script 

An easy-to-navigate and powerful Python-based library for data analysis using Streamlit. The script includes pandas for data manipulation, NumPy for mathematical computations, Seaborn, and matplotlib for data visualizations.

## Getting Started

This script helps you analyze your Employee Dataset with a variety of data analysis techniques.

#### Prerequisites

The following libraries are needed : 
- Pandas 
- Numpy 
- Seaborn 
- Matplotlib 
- Streamlit

Install the packages using pip:

```cmd
pip install pandas numpy seaborn matplotlib streamlit
```

## Instructions

Once these libraries are installed, the project can be run by using this command in your terminal:

```
python -m streamlit run main.py
```

## Dataset Details

Your dataset should be in csv format. Here, we are working with the `Train_Dataset.csv` and `Test_Dataset.csv`.

The snippet of the Dataset is as follows:

```
   EmployeeID  Attrition   Age TravelProfile Department  HomeToWork  \
0   5110001.0        0.0  35.0        Rarely  Analytics         5.0   
1   5110002.0        1.0  32.0           Yes      Sales         5.0   
2   5110003.0        0.0  31.0        Rarely  Analytics         5.0   
3   5110004.0        0.0  34.0           Yes      Sales        10.0   
4   5110005.0        0.0  37.0            No  Analytics        27.0
```
Please ensure the path of the dataset is correct by modifying it according to your directory in this line: 

```python
"train_data=pd.read_csv(\"Train_Dataset.csv\")"
"test_data=pd.read_csv(\"Test_Dataset.csv\")"
```

## Future Work

This is a simple README.md for your Python project. However, this could be elaborated in future versions including samples, environment setup, complete installation guide, and support and contribution sections, etc.

## Contact

If you have a problem or would like to discuss something about this document, feel free to open an issue in this repo.

## License 

This project is open source and available to all under the MIT license.

## Acknowledgements

**Happy data analysis!**