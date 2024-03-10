# LlaVa Multi-modal Streamlit Web-App

In this project I utilize the [Large Language and Vision Assistant](https://llava-vl.github.io/) multi-modal LLM to create a Streamlit Web-App.

* LLaVa takes as input both images and text and provides text based answers. It is an open-source foundation model that mimics the multi-modal capabilities of GPT-4.
* [Streamlit](https://docs.streamlit.io/) is an easy to use open-source Python library to develop customizable Web-Apps for Machine Learning projects.
* I access the LLaVA 1.5 model with 13 Billion parameters via the [Replicate](https://replicate.com/docs) LLM hosting platform.
* In this application the user can choose between both LlaVa and  OpenAI's [DaLLE](https://openai.com/dall-e-3).

## Run the Web-App

```
    treamlit run main.py
```

## Replicate Conda Environment

```
    conda env create --file environment.yaml
```

## Activate the environment

```
    conda activate llava_multimodal
```