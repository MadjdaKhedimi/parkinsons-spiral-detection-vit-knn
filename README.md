# ViT-KNN for Parkinson's Disease Detection

[![Paper](https://img.shields.io/badge/Paper-Bioengineering-blue)](https://www.mdpi.com/2306-5354/11/12/1218)

Vision Transformer + KNN hybrid model achieving **96.77% accuracy** for Parkinson's Disease detection from spiral drawings.

**Paper:** [Architecture-Aware Augmentation: A Hybrid Deep Learning and Machine Learning Approach for Enhanced Parkinson's Disease Detection](https://www.mdpi.com/2306-5354/11/12/1218) (Bioengineering, 2024)

## Overview

This notebook implements our best-performing model combining Vision Transformer for feature extraction with K-Nearest Neighbors for classification. Key finding: the model performs best on original, unaugmented data (96.77% accuracy), demonstrating that data augmentation strategies must be architecture-aware.

## Installation
```bash
git clone https://github.com/MadjdaKhedimi/vit-knn-parkinsons-detection.git
cd vit-knn-parkinsons-detection
pip install -r requirements.txt
jupyter notebook "ViT with KNN.ipynb"
```

## Requirements

- Python 3.8+
- PyTorch, torchvision
- scikit-learn
- numpy, pandas, matplotlib
- Jupyter Notebook

## Citation
```bibtex
@article{khedimi2024architecture,
  title={Architecture-Aware Augmentation: A Hybrid Deep Learning and Machine Learning Approach for Enhanced Parkinson's Disease Detection},
  author={Khedimi, Madjda and Zhang, Tao and Merzougui, Hanine and Zhao, Xin and Geng, Yanzhang and Djaroudib, Khamsa and Lorenz, Pascal},
  journal={Bioengineering},
  volume={11},
  number={12},
  pages={1218},
  year={2024},
  doi={10.3390/bioengineering11121218}
}
```

## Contact

**Madjda Khedimi**  
PhD Candidate, Tianjin University  
khedimimadjda@gmail.com  
[LinkedIn](https://www.linkedin.com/in/madjda-khedimi-336154162/) | [Google Scholar](https://scholar.google.com/citations?user=CCoU9aQAAAAJ)

## License

MIT License
