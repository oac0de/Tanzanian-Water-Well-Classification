
# Project Introduction
Tanzania is in the midst of a water crisis. 1/3 of the land is an arid desert and there is very limited access to clean water for residents that don’t live near one of the three major lakes on the border of the country. The Tanzanian government and several private companies have built drinking water wells all around the country, however their water pumps don’t work much of the time. Many people resort to drinking contaminated groundwater (found openly), while pollution runs largely unregulated, leaving the possibilty of health problems in the open. The people need our help!

# Goals 
The goal of this project is to perform a ternary classification of the functionality of water wells in Tanzania. I will use data originally obtained from taarifa, an open-source API, and the Tanzanian Ministry of Water. I will practice and demonstrate the employment of logistic regression, by training and testing multiple supervised ensemble methods of machine learning. The deliverable will be visualizations of the most important features for proper classification using the most accurate model.

## Importing necessary libraries

## Obtain Data

## Cleaning our data

### Dealing with missing values

#### "funder"

#### "installer"

#### "subvillage"

#### "public_meeting"

#### 'scheme management'

#### "scheme_name"

#### 'permit' 

#### 'wpt_name'

### Checking for placeholder values

#### 'recorded_by'

#### 'longitude' & 'latitude'

#### 'num-private'

#### 'construction_year'

### Removing "duplicate" features

#### 'funder' vs 'installer'

#### 'extraction_type', 'extraction_type_group', & 'extraction_type_class'

#### 'payment' vs 'payment_type'

#### 'water_quality' vs 'quality group'

#### 'quantity' vs 'quantity_group'

#### 'source' vs 'source_type'

#### 'waterpoint_type' vs  'waterpoint_type_group']

#### 'region' vs 'region_code'

#### 'management' vs 'management_group'

### Date/Time data

#### 'date-recorded'  & 'construction_year'

## EDA

<img src="output_138_0.png">

### Does location have anything to do with well functionality?


![png](output_141_0.png)

![png](output_144_0.png)

![png](output_145_0.png)

### Does water-quality have an effect on functionality?

![png](output_148_0.png)

### 'water_quantity' vs status

![png](output_151_0.png)

![png](output_152_0.png)

### Population Points by Quantity and Status

![png](output_155_0.png)

![png](output_158_0.png)

### 'installer' vs status

![png](output_164_0.png)

### 'Extraction_type'

![png](output_167_0.png)

### Management vs Status 
#### 'scheme_management'

![png](output_170_0.png)

#### 'management'

![png](output_172_0.png)

## Dealing with Categorical Variables

### One-hot-encode object/categorical columns 

#### 'installer'

#### 'basin'

#### 'region'

#### 'lga' & rest

##### 'extraction_type_class'

##### 'management'

##### 'payment_type'

##### water_quality

##### quantity

##### source

##### source_class

##### waterpoint_type

## Finding the best ML Model

### Importing modeling libraries

### Baseline KNN

#### Tuned KNN

### Baseline Random Forest

#### RF SMOTE resample

#### RF Tuning

#### Best Feature Importance

### XGBoost

### Decision Tree

## Best Performing Model Visualizations

#### Water Quantity by Status

![png](output_301_0.png)

#### Quantity & Location

![png](output_303_0.png)

#### Age, Location & Functionality

![png](output_307_0.png)

#### Well Status by Age

![png](output_310_0.png)

![png](output_313_0.png)

#### Extraction Type Class by Functionality

![png](output_315_0.png)
