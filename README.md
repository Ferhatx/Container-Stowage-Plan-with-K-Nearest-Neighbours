
# K-Nearest Neighbor and Container Stowage

This project aims to prevent structural damage and environmental pollution caused by incorrect container loading on cargo ships. Improper stowage can result in structural breakage, listing (capsizing), and massive financial losses for shipowners, as well as significant marine pollution.

The system I developed ensures safe container distribution by maintaining the ship's balance, assigning containers to the most suitable holds. This not only preserves ship stability but also minimizes unloading costs.

The project runs stably on all ships with six cargo holds.

## How It Works

1.The ship’s cargo hold structure and current load status are input.

2.New container weight and dimension details are provided.

3.The KNN algorithm predicts the most suitable cargo hold based on historical data.

4.The system suggests the optimal placement and minimizes unloading costs.


## Features

- Container loading algorithm that helps maintain ship stability
- Container placement decisions using the K-Nearest Neighbors algorithm
- Automatic selection of the most suitable cargo hold
- Optimization of unloading costs
- Real-time decision support system


## Dataset

- A sample dataset containing container information is included as a dataset.csv file.

- The model is trained using historical loading data and cargo hold details.


## Usage

Run the script:

```bash
  python ship.py
```
    
## Technologies and Libraries Used

- Python
- `math`
- `random`
- `pandas`
- `scikit-learn` → `KNeighborsClassifier`


## Authors

- [@Ferhatx](https://www.github.com/Ferhatx)

