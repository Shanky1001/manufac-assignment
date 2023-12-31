
# Manufac Frontend Assignment

Need to create Gamma Table and Flavanoids Table with Mean, Median and Mode

## Description

This project calculates class-wise statistics for Gamma and Flavanoids based on the provided data.

## Installation

Install the project with yarn

1. Clone the repository.
2. Run the following commands in terminal to install the dependencies.

```bash
  yarn install
  cd manufac assignment
```
## Run the project

Install the project with yarn

1. Run the following commands in terminal to run the project.

```bash
  yarn start
```
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Usage

### Flavanoids Table

1. Import the required data and utility functions from the respective files.
2. Call the `calculateClassStatistics` function with the data to calculate class-wise statistics for Flavanoids.
3. Use the calculated statistics to display the Flavanoids table.

```javascript
import data from '../assets/data.json';
import { calculateMean, calculateMedian, calculateMode } from '../utils/helper';

// Rest of the code

```

### Gamma Table

1. Import the required data and utility functions from the respective files.
2. Call the `calculateClassStatistics` function with the data to calculate class-wise statistics for Gamma.
3. Use the calculated statistics to display the Gamma table.

```javascript
import data from '../assets/data.json';
import { calculateMean, calculateMedian, calculateMode } from '../utils/helper';

// Rest of the code

```

### Utility functions

You could find the utility functions in `utils/helper`.

Utility function to calculate the `mean, median and mode`.

### Results

![image](https://github.com/Shanky1001/manufac-assignment/assets/108118506/9b71d212-513a-4659-95aa-47376f8a8386)


