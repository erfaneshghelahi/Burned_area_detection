# Burnt Area Detection Using Sentinel-2 Data: K-means vs. Random Forest

This project focuses on detecting and mapping burnt areas using Sentinel-2 multi-spectral satellite data in the Alpes-Côte d'Azur province, during a wildfire event in August. The project compares two algorithms, **K-means** (unsupervised) and **Random Forest** (supervised), to assess their accuracy in delineating burnt areas in heterogeneous landscapes.

## Key Features
- **Algorithms Used**: K-means clustering and Random Forest classification.
- **Data**: Pre-fire and post-fire Sentinel-2 raster data.
- **Study Area**: Alpes-Côte d'Azur, between August 2 (pre-fire) and August 27 (post-fire).
- **Burnt Area Estimation**:
  - **Random Forest (RF)**: 96% accuracy for both pre-fire and post-fire data, estimating 2.33 Kha of forest burnt and a total of 5.27 Kha (forest and non-forest).
  - **K-means**: Estimated 7.37 Kha of total burnt area.

## Results
- **Random Forest** classifier provides higher accuracy and more reliable burnt area estimations compared to K-means.
- Ground truth estimates suggest a total burnt area between 5,000-6,000 hectares, with around 2.82 Kha of forest burnt.
- Despite being computationally intensive, RF outperforms K-means in precision, making it a better tool for burnt area mapping in complex landscapes.

## Tools & Technologies
- **Satellite Data**: Sentinel-2 (pre-fire and post-fire)
- **Algorithms**: K-means, Random Forest
- **Languages**: Python (for processing and analysis)
