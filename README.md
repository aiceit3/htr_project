# htr_project
├── README.md          <- The top-level README for developers using this project.
├── data               <- BẮT BUỘC
│   ├── external       <- Data from third party sources. (Tham khảo)
│   ├── interim        <- Intermediate data that has been transformed. (Tham khảo)
│   ├── processed      <- The final data sets for modeling. (Tham khảo)
│   └── raw            <- The original, immutable data dump. (Tham khảo)
│
├── docs               <- CHỨA TÀI LIỆU THAM KHẢO
│
├── models             <- CHỨA MODELS ĐÃ HUẤN LUYỆN: Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. (file google colab để tìm ra model)
│
├── src                <- (CHÍNH) Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- (LOAD DL VÀ TẠO DL...) Scripts to download/generate/process data
│   │   └── make_dataset.py (còn nữa ...)
│   │
│   ├── models         <- (HUẤN LUYỆN MODEL)Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py (Chưa tìm hiểu)
│   │   └── train_model.py (Chưa tìm hiểu)
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│   |    └── visualize.py
|   └── view           <- Giao diện
|   |
└───└── main.py
|
├── setup.py           <- (không cần thiết)Make this project pip installable with `pip install -e` (PIP LỆNH ĐỂ CÀI ĐẶT THƯ VIỆN)
└── references         <- (không cần thiết)TÀI LIỆU NÓI VỀ DỮ LIỆU: Data dictionaries, manuals, and all other explanatory materials.
Link tham khảo: 
- https://drivendata.github.io/cookiecutter-data-science/
- https://github.com/arthurflor23/handwritten-text-recognition
- https://github.com/githubharald/SimpleHTR
