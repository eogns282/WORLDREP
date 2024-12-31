# WORLDREP: A Dataset for Forecasting Future International Events

> 🚀 **[Dataset on Hugging Face](https://huggingface.co/datasets/Daehoon/WORLDREP)**  

WORLDREP (**WORLD Relationship and Event Prediction**) is a high-quality dataset designed for predicting future international events based on textual information, such as news articles. It provides labeled relationships between countries with confidence scores ranging from **0.0 (cooperation)** to **1.0 (conflict)**.

This dataset is introduced and detailed in the following paper:  
[**Forecasting Future International Events: A Reliable Dataset for Text-Based Event Modeling**](https://arxiv.org/abs/2411.14042)

---

## Dataset
The WORLDREP dataset is publicly available on Hugging Face:  
[![Hugging Face Dataset](https://img.shields.io/badge/Dataset-Hugging%20Face-blue)](https://huggingface.co/datasets/Daehoon/WORLDREP)

### Dataset Structure
The dataset features the following columns:
| Column       | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| `EventID`    | Unique identifier for the event                                            |
| `SourceURL`  | URL of the news article reporting the event                                |
| `DATE`       | Publication date of the article in `YYYYMMDDHHMMSS` format                |
| `Country1`   | The first country involved in the event                                    |
| `Country2`   | The second country involved in the event                                   |
| `Score`      | Numerical value (0.0-1.0) representing the relationship between countries. A score close to **0.0** indicates **cooperation**, while a score close to **1.0** indicates **conflict**. |

---

## Code
The code for data preprocessing, analysis, and usage will be released **soon**.

---

## Citation
If you use WORLDREP in your research, please cite the following paper:
```
@inproceedings{gwak2024worldrep,
title={Forecasting Future International Events: A Reliable Dataset for Text-Based Event Modeling},
author={Daehoon Gwak, Junwoo Park, Minho Park, Chaehun Park, Hyunchan Lee, Edward Choi and Jaegul Choo},
booktitle={EMNLP Findings},
year={2024}
}
```

---

## Links and Resources
- 📄 [Paper on arXiv](https://arxiv.org/abs/2411.14042)  
- 📊 [Dataset on Hugging Face](https://huggingface.co/datasets/Daehoon/WORLDREP)

---

## Contributing
If you encounter any issues or have feature requests, feel free to open an issue or a pull request.

---

## License
This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).
