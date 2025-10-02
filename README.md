# iSCMS2025-Hackathon
Peak vs Noise Detection Algorithm Developed for Hackathon event at iSCMS2025 Conference
This code was developed leveraging ChatGPT with the general prompt guidance that I wanted it to analyze the training dataset and create an algorithm that would predict whether signals from the "test" dataset were real or noise. The code can be executed as a Jupyter notebook.

Per the response from ChatGPT, the code works through the following steps:
1) Upload train.csv + test.csv
2) Train the model
3) Save + apply the model
4) Download test_predictions.csv

The performance was reported to be:
Accuracy - 93.07%
Precision - 93.94%
Recall - 98.83%
F1 Score - 96.32%

To recreate these results, simply upload the code to a Jupyter notebook, run, and upload the train.csv and test.csv files when prompted. The code should generate a test_predictions.csv file that contains a column specifying whether each row was determined to be a real peak or noise.
