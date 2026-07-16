# Label_Studio

# Label Studio Class Filtering

This repository contains the dataset and documentation for isolating specific class annotations from a Label Studio object detection/classification project.

## Project Structure
* `data/data.json`: The complete dataset exported directly from Label Studio.
* `filter.py`: A Python script to parse the JSON structure and filter tasks by a specific class label.

## How to Run the Filter
1. Clone this repository.
2. Open `filter.py` and update the `TARGET_CLASS` variable to your desired class name.
3. Run the script using:
   ```bash
   python filter.py
