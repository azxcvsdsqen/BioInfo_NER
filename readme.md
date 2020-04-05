Readme

python=3.6
pytorch=1.1

Following [BioBERT](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506) the data used in our paper can be found at https://github.com/dmis-lab/biobert#datasets (or this [link](https://drive.google.com/open?id=1OletxmPYNkz2ltOr9pyT0b0iBtUWxslh)).

To run our code, you first need to set the environment up and download biobert from https://github.com/naver/biobert-pretrained and put it into biobert_pyt directory (please use our config.json file).

If the model is tf version, you need to convert it to pytorch version. https://github.com/huggingface/transformers.

Also, you need to replace original the config.json in your model directory with the config.json in the bert model directory provided by us.

You can run run.sh directly to train and evaluate our model on the sample data.
