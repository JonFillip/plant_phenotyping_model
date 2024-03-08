# README: Two-Stage Deep Learning Approach to Plant Phenotyping

## Project Overview

This project presents a novel two-stage deep learning-based framework designed for the precise analysis and characterization of tomato plants within vertical farming environments. Grounded in a blend of cutting-edge research and practical implementation, this approach aims to set a new precedent in agricultural phenotyping, particularly for vertical farms focusing on tomato cultivation.

### Implementation Overview

The research encapsulates a dual-phase methodology aimed at the detection, localization, and segmentation of tomatoes, followed by an in-depth trait analysis. This approach is inspired by the successful application of the Mask R-CNN model in agricultural segmentation tasks and is tailored to address the unique challenges presented by vertical farming conditions.

#### Stage 1: Detection, Localization, and Segmentation

The first phase of the methodology utilizes the Mask R-CNN model to detect, locate, and accurately segment individual tomatoes from complex backgrounds, notwithstanding potential occlusions. This technique is not only precise but also versatile, allowing for the categorization of tomatoes into various classes based on their distinctive characteristics.

#### Stage 2: Trait Extraction and Analysis

Following successful segmentation, the second phase focuses on the extraction and quantification of key tomato traits, specifically counting and maturity indices. This stage is crucial for assessing harvestability and optimizing yield within the vertical farming context.

### Dataset

The dataset employed in this project is derived from Laboro's AI tomato dataset, which provides a rich collection of tomato images from a greenhouse vertical farm. This dataset captures a wide range of tomato sizes and ripening stages, making it an ideal resource for training, validating, and testing our model.

## Getting Started

To utilize this framework, ensure you have the following prerequisites installed on your system:

- Python 3.8 or higher
- PyTorch 1.7 or higher
- torchvision 0.8.1 or higher
- pycocotools

The project's code is contained within a Jupyter notebook titled `plant_phenotype_prototype_torchvision_maskrcnn50FPN_v1.ipynb`, which provides a step-by-step guide through both stages of the methodology, from initial image processing to the final trait analysis.

### Installation

1. Clone the repository or download the project files to your local machine.
2. Install the required Python packages:

```bash
pip install torch torchvision pycocotools
```


### Usage

Follow the instructions within the notebook to:

- Preprocess the dataset.
- Train the Mask R-CNN model on the provided tomato dataset.
- Perform detection, localization, and segmentation of tomatoes.
- Extract and analyze tomato traits.

### Model Predictions and Results

Here are some examples of the model's predictions on the tomato dataset. These images demonstrate the model's ability to accurately detect, segment, and classify tomatoes in a complex vertical farming environment.


Figure 1: Tomato detection and segmentation results.





Figure 2: Extracted tomato traits including count and maturity indices.


### Contributing

We welcome contributions from the community, whether it's through reporting bugs, providing feedback, or submitting pull requests. Please refer to our contribution guidelines for more information on how to participate in the project's development.

### Citation

If you use this framework or the associated dataset in your research, please consider citing the following:

- Laboro's AI Tomato Dataset. Available here at [Laboro Tomato 🍅](https://github.com/laboroai/LaboroTomato/tree/master)
- Ni, X., Li, C., Jiang, H., Xu, X., Han, S., Qu, M., & Cao, K. 2020. [Deep learning image segmentation and extraction of blueberry fruit traits associated with harvestability and yield](https://www.nature.com/articles/s41438-020-0323-3)
