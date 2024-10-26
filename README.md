# Memorizing Normality to Detect Anomaly: Memory-Augmented Deep Autoencoder for Unsupervised Anomaly Detection

**Objective**  
This project presents a **Memory-Augmented Deep Autoencoder (MemAE)** for unsupervised anomaly detection, designed to overcome limitations in traditional autoencoders by incorporating a memory module. MemAE is trained solely on normal data, with a unique memory module that reconstructs input patterns by selectively addressing prototypical elements from memory. By leveraging sparse memory addressing, MemAE improves anomaly differentiation by amplifying reconstruction errors for abnormal inputs. Experimental results across various datasets demonstrate the effectiveness of MemAE, achieving higher accuracy in anomaly detection tasks by focusing on memorizing and reconstructing only normal data patterns.

## Project Structure

- **Data Preprocessing**: Covers data loading, cleaning, and necessary transformations for preparing the data.
- **Exploratory Data Analysis (EDA)**: Provides an initial analysis to understand data distributions and identify patterns.
- **Model Training**: Trains the Memory-Augmented Deep Autoencoder with specific configurations to enhance anomaly detection.
- **Results and Visualization**: Analyzes model performance through metrics and visualizations that show reconstruction error differences between normal and anomalous data.

## Requirements

- **Python Version**: 3.x
- **Libraries Used**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` or `pytorch` (depending on your implementation)
  - Any additional libraries needed for memory-augmented networks


