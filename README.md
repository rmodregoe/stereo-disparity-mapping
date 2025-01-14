# Stereo Image Analysis and Disparity Mapping

## Project Description
This project explores stereo image analysis through disparity mapping. Techniques like Sum of Squared Differences (SSD) and normalized correlation are implemented to calculate disparity maps for left-to-right and right-to-left stereo matching. The project also analyzes the effects of noise and contrast variations and compares results with ground truth images.

## Features
- **Disparity Mapping**:
  - Implements SSD and normalized correlation for stereo matching.
- **Noise and Contrast Analysis**:
  - Evaluates the impact of Gaussian noise and contrast enhancement on disparity maps.
- **Comparison**:
  - Compares generated disparity maps with ground truth images.

## Included Files
1. **Code**:
   - `stereo_analysis.ipynb`: Jupyter Notebook for the project implementation.
2. **Images**:
   - `PS2-1-a-1.png`, `PS2-1-a-2.png`: Stereo image pair.
   - `PS2-2-a-1.png`, `PS2-2-a-2.png`: Second stereo image pair.
   - `PS2-2-b-1.png`, `PS2-2-b-2.png`: Ground truth images for the second pair.

## Requirements
- **Python**: Version 3.8 or higher
- Required Libraries:
  - `numpy`
  - `opencv-python`
  - `matplotlib`

Install dependencies using:
```bash
pip install numpy opencv-python matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/rmodregoe/stereo-disparity-mapping.git
   ```
2. Open `stereo_analysis.ipynb` in Jupyter Notebook.
3. Follow the instructions to execute the code and visualize the results.

## Results
- Outputs include disparity maps for various stereo image pairs.
- Analysis of the impact of noise and contrast on disparity results.
- Comparison of generated maps with ground truth images.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
Created by Ricardo Modrego. For questions or feedback, contact me at [r.modrego.e@gmail.com](mailto:r.modrego.e@gmail.com).
