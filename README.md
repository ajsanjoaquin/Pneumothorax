## Pneumothorax Classifier
* I made an image classifier to detect Pneumothorax (collapsed lung) on x-ray scans. It is trained on a Resnet 50 CNN model.
* AUC was recorded at 89% for the best version of the model. Pretty good compared with the 96% AUC of a CNN model made by [Gooßen, et. al.](https://arxiv.org/abs/1907.07324) and considering this was done within 2 days.
* Data was taken on a synthetic dataset provided by the National University Hospital (NUH) and Massachusets Institute of Technology Critical Care (MIT Critical Care). Data is not provided.
* Pneumothorax_code.ipynb: Main notebook I used to train the model. I retroactively added markdown for clarity.
* Test_1024.ipynb: Saved checkpoint of 1024 x 1024 images but I discontinued training because it was inefficient. Code is provided as-is.
