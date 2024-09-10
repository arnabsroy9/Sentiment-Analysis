# Sentiment Analysis
This system is for sentiment analysis from Bengali text.  

## Installation 

Clone repo and install required dependencies.

```

git clone https://github.com/arnabsroy9/Sentiment-Analysis.git
cd Sentiment-Analysis
pip install -r requirements.txt

```

Download the model weight from [here](https://drive.google.com/drive/folders/1EuHZStggkSZIfltNuNvyttey6ZPrdvD9). 

Copy pytorch_model.bin file paste to Sentiment-Analysis/app/sentiment

### You're ready to go...

## Inference 

Open terminal in Sentiment-Analysis and execute: 
```
uvicorn main:app --reload
```
## Output preview

![Output Preview](./assets/output.jpg)
