# Discord Spam Detection


## Introduction

We aim to build a bot to detect and remove spam messages on the [66 Days of Data](https://discord.gg/wV2x8KMSeC) server. 

## Project timeline

* Dataset collection: 2 months
* Model building 2 months
* Discord bot coding and deployment: 2 months
* Blog publishing: 2 weeks

## Authors (alphabetic order)

* [William Guesdon](https://github.com/wguesdon)

## Authors contribution

* [William Guesdon](https://github.com/wguesdon):
	* Configuration of GitHub for the project. 
	* Developing a Naive Bayes model based on the Kaggle Email Dataset.
* [Rea Kalampaliki](https://github.com/ReaKal): Coming soon.

## ToDo List

```
x Collect relevant datasets for the project -> William, Rea
. Research method for the scrapping of Discord server message. -> William
. Research examples of spam detection models: Jayashree
	. Naive Bayes
	. Logistic regression
	. Neural Network
. Build and test a SPAM detection model. :Jayashree
. Research how to code a discord bot with python.
. Research how to deploy a discord bot on AWS
. Build the SPAM detection bot.
. Deploy the SPAM detection bot on AWS.
```

## Datasets

* [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
* [Email Spam](https://www.kaggle.com/veleon/ham-and-spam-dataset)
* [Spam or Not Spam Dataset](https://www.kaggle.com/ozlerhakan/spam-or-not-spam-dataset)
* [Spam Classification for Basic NLP](https://www.kaggle.com/chandramoulinaidu/spam-classification-for-basic-nlp)

## Structure of the repository

#### methods/
Contains the instruction to set up the environment.

#### notebooks/
Contains the notebooks used for 
* EDA.
* Resizing the dataset.
* experimenting with ML models.

#### src/
Contains the libraries built to  build the training set, train final ML models.

#### dev/
Directory to be used for development. Each of the authors having one folder to upload scripts and notebooks in development.

#### file-tree structure/

```
├── README.md          <- The top-level README for developers using this project.
│
├── methods           <- Instruction for environment set up
│
├── notebooks          <- Key Jupyter notebooks 
│
├── src                <- Source code for use in this project.
│
├── dev         <- Directory for development in progress
```
