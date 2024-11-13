# Guitar and Bass Guitar Dataset

## Description
This dataset contains detailed information on 113 guitars and 20 bass guitars, including attributes such as maker, model, introduction year, notable users, features, popularity, and finishes. With up to five features and finishes per record, the dataset provides a comprehensive overview of each instrument’s characteristics and historical context.

The guitar dataset includes records with varying levels of detail: most entries contain three features and three finishes, with 111 entries listing four features, and two entries including five. Additionally, the dataset highlights 53 guitars used by notable musicians, collectively representing 88 unique individuals, offering insights into the associations between renowned users and specific guitar models. This dataset serves as a valuable resource for analyzing guitar attributes and understanding the guitar’s impact on music history.

## Dataset Structure
The dataset consists of the following key columns:
- **Maker**: The manufacturer or brand of the guitar/bass guitar (e.g., Fender, Gibson).
- **Model**: The specific model name of the guitar/bass guitar.
- **Introduction Year**: The year the guitar/bass guitar model was introduced.
- **Notable User 1, 2, 3**: Names of notable musicians associated with each guitar/bass model (up to three users per entry).
- **Features 1, 2, 3, 4, 5**: Core features of each guitar, with up to five listed for some models (e.g., "Single-coil pickups," "Tremolo bridge").
- **Popularity**: A metric indicating the popularity level of each guitar or bass guitar.
- **Finish 1, 2, 3, 4, 5**: Different finish options available for each guitar or bass guitar model (e.g., "Sunburst," "Black").

## Key Insights
- **Notable Users**: The dataset features 53 guitars associated with famous musicians, highlighting 88 unique users. This diverse range of notable musicians reflects the cultural significance and popularity of certain guitar models.
- **Features and Finishes**: Most guitar records include three features and finishes, but some contain up to five. This level of detail allows for an in-depth analysis of the attributes that distinguish each model.
- **Popularity**: An indicator of each model’s standing within the guitar community or music industry.

## Potential Use Cases
This dataset is useful for:
- **Musical History Analysis**: Studying the evolution and characteristics of iconic guitar and bass guitar models.
- **Market Research**: Understanding the attributes and finishes preferred by notable musicians.
- **Trend Analysis**: Identifying popular features and finishes over time.
- **Machine Learning**: Training models to predict guitar popularity based on features, finishes, and user associations.

## File Format
- The dataset is provided in CSV format, with rows representing individual guitar and bass guitar models, and columns containing various attributes.

## Getting Started
1. **Download the dataset** and save it in a location of your choice.
2. Load the dataset into your preferred data analysis environment (e.g., Python, R, Excel) for exploration and analysis.

### Sample Code to Load Dataset (Python)
```python
import pandas as pd

# Load the dataset
data = pd.read_csv("GuitarModels.csv")
data = pd.read_csv("Guitar_Bass_Dataset.csv")

# Display the first few rows
print(data.head())
