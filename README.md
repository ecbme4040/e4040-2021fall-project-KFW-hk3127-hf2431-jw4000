## Instructions:
We have three folders. Alexnet_model, VGG_model and Lenet_model. Each folder has several jupyter notebooks.One single notebook corresponds to a full
precision version or a combination of M,N for the corresponding nueral network. For each notebook, we must ensure that the version of tensonflow is tensorflow 2.7.0. In each notebook, there are several parts including data loading, class construction, model construction ,model training and model evaluation. We use cifar100 in tensorfow.keras as our dataset, so we just load it in notebook calliing a function. Just run the cells in order for each notebook.

# Organization of this directory

```./
├── Alexnet_model
│   ├── AlexNet_3_3.ipynb
│   └── AlexNet_FP.ipynb
├── E4040.2021Fall.KFW.report.hk3127.hf2431.jw4000.pdf
├── Lenet_model
│   ├── LeNet_3_1.ipynb
│   ├── LeNet_3_3.ipynb
│   ├── LeNet_3_5.ipynb
│   ├── LeNet_5_5.ipynb
│   └── LeNet_FP.ipynb
├── README.md
├── VGG_model
│   ├── VGG_3_1.ipynb
│   ├── VGG_3_3.ipynb
│   ├── VGG_3_5.ipynb
│   ├── VGG_5_3.ipynb
│   ├── VGG_5_5.ipynb
│   └── VGG_FP.ipynb
└── utils
    ├── cifar_utils.py
    ├── image_generator.py
    ├── layer_funcs.py
    ├── neuralnets
    │   ├── cnn
    │   │   ├── LeNet_trainer.py
    │   │   ├── model_LeNet.py
    │   │   ├── my_LeNet_trainer.py
    │   │   └── my_model_LeNet.py
    │   └── mlp.py
    ├── optimizers.py
    └── reg_funcs.py

6 directories, 25 files
