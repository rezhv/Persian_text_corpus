# Colloquial Persian Corpus from Telegram

## Overview
This repository hosts the Colloquial Persian Corpus, the largest available dataset of its kind scraped from public Telegram channels. It provides an extensive collection of conversational Persian language data, ideal for various applications in natural language processing and linguistic research.

## Dataset Details

### Source
The data was meticulously collected from Telegram, focusing on public channels. These channels were identified and curated by our team of agents, dedicated to exploring and discovering relevant content.

### Dataset Statistics
- **Largest Available Corpus to Date**
- **Average Length of Document**: 46 tokens
- **Number of Documents**: 188,874,296
- **Number of Channels Scraped**: 58,000
- **Uncompressed Size**: 123 GB
- **Channels List**: Available in `channels.json`

### Data Collection Method
The data was collected using a Python script employing the Telegram API. The script systematically scrapes messages from a list of public channels, which are constantly updated and stored in `channels.json`. The scraping process involves iterating through each channel, fetching messages, and discovering new channels through forwarded messages. The collected data is then stored in CSV format for each channel. This automated and comprehensive approach ensures a wide coverage of channels and messages.

### Access to the Dataset
The complete dataset can be accessed [here](https://drive.google.com/drive/folders/1gbNf9tnpld4UXdpp-AXW7S_QhTcccxEx?usp=sharing).

## Usage
This dataset is intended for academic research and development in the fields of natural language processing, computational linguistics, and machine learning. We encourage its use for language models, sentiment analysis, colloquial language studies, and more.

## Citation
If you use this dataset in your research, please cite it as follows:
[Alireza Havaei], (2023). Colloquial Persian Corpus from Telegram. [Online]. Available: https://github.com/rezhv/Persian_text_corpus/
