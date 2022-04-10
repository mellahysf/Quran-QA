# Quran-QA

## How to run the Code? <br>

1) Create an account in Google Cloud Platform (GCP) <br>
2) Create a bucket in the GCP created on 1) (the name of ours which is private is "t5finetuning") <br>
3) Create a base dir in the backet created on 2) for storing your data (the name of ours is "dataset") <br>
4) Create a model dir in the backet created on 2) for storing yout trained models (the name of ours is "models-quranqa-mt5-XL-v4") <br>
5) Convert your dataset files (train and dev) to Tabulate-Separate-Values (TSV files). One line in each file should looks like following: <br>
	question: the quesion context: the passage</s> tabulation (or \t) answer <br>
	==> in this sens you should create two files: train.tsv and dev.tsv <br>
6) For exporting and saving the best checkpoint, create the export model dir in the backet created on 2) (the name of ours is "export-v3-XL") <br>

## Then you can run the code. <br>

## Thanks to the Qur'an QA 2022 Shared Task for the great competition and the QRCD Dataset. <br>
For more information about the task, the competition and the official evaluation, please see the following links: <br>
	-https://sites.google.com/view/quran-qa-2022/home?authuser=0 <br>
	-https://gitlab.com/bigirqu/quranqa <br>
