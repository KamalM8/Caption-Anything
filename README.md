# Caption Anything in Any Style

We build an appealing demo by combining [Segment Anything](https://github.com/facebookresearch/segment-anything), Visual Captioning, and [ChatGPT](), which is capable to caption any pieces in the image in various language styles.

Caption-Anything supports both visual controls and textual controls: 
### Visual Controls
* Click
* Box
* Everything
* Cutouts
* Track

### Language Controls
* Length
* Sentiment
* Wikipedia Search
* Template sentence


# RUN
```
# set transformer cache dir (optional)
export HF_HOME=/your/path/to/cache/huggingface/ 

# set openai api key
export OPENAI_API_KEY={Your_Private_Openai_Key}

# set the proxy api if you can not access official api (https://api.openai.com/v1)
export OPENAI_API_BASE=https://openai.1rmb.tk/v1/

# run caption-anything model
python caas.py
```