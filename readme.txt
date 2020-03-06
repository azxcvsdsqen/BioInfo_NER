Readme

python=3.6
pytorch=1.1

To run our code, you first need to set the environment up and download biobert from https://github.com/dmis-lab/biobert

If the model is tf version, you need to convert it to pytorch version. https://github.com/huggingface/transformers.

Also, you need to replace original the config.json in your model directory with the config.json in the bert model directory provided by us.

You can run run.sh directly to train and evaluate our model on the sample data.