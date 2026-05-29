
<div align="left">

```
██████╗  █████╗ ███╗   ███╗██╗████████╗    ██████╗ ██╗   ██╗██████╗ ████████╗ █████╗ 
██╔══██╗██╔══██╗████╗ ████║██║╚══██╔══╝   ██╔════╝ ██║   ██║██╔══██╗╚══██╔══╝██╔══██╗
██████╔╝███████║██╔████╔██║██║   ██║      ██║  ███╗██║   ██║██████╔╝   ██║   ███████║
██╔══██╗██╔══██║██║╚██╔╝██║██║   ██║      ██║   ██║██║   ██║██╔═══╝    ██║   ██╔══██║
██║  ██║██║  ██║██║ ╚═╝ ██║██║   ██║      ╚██████╔╝╚██████╔╝██║        ██║   ██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝   ╚═╝       ╚═════╝  ╚═════╝ ╚═╝        ╚═╝   ╚═╝  ╚═╝
```

</div>

<div align="centre">

```
> whoami
  Ramit Gupta — AI/ML Engineer
  Delhi-NCR, India

> cat focus.txt
  ML | DL | Computer Vision | Generative AI | AWS
```

</div>

---

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&pause=1000&color=00FF41&width=650&lines=%24+python+train.py+--model+transformer+--from+scratch;%24+yolo+detect+--source+satellite.jpg;%24+aws+sagemaker+deploy+--model+cnn_change_detection;%24+opencv+--realtime+--detection+objects;%24+fastapi+--app+hospital_inference+--shap+explain;%24+git+push+origin+main+%23+shipped+%E2%9C%85" alt="Typing SVG" />

---

## `~/projects`

---

### [`Hospital_Management_System`](https://github.com/Ramit-Gupta23/Hospital_Management_System) — End-to-End Hospital ML Platform

```
patient data ──► feature engineering ──► XGBoost ──► LOS prediction
                                                  └──► SHAP explainability
                                                            │
                                        FastAPI inference API ◄─── Docker Compose
                                                            │
                                              Streamlit dashboard ──► AWS EC2
```

> XGBoost predicts Length of Stay. SHAP makes predictions explainable per-patient. FastAPI serves inference. Streamlit visualizes. Docker Compose ties it all together. Deployed live on AWS EC2.

`XGBoost` `SHAP` `FastAPI` `Streamlit` `Docker Compose` `AWS EC2` `Jupyter`

---

### [`TerraStorm`](https://github.com/Ramit-Gupta23/TerraStorm-Cloud-Native-Land-Monitoring) — Cloud-Native Land Change Detection

```
S3 upload ──► Lambda trigger ──► SageMaker CNN ──► change map ──► Django dashboard
                                                             └──► SNS alert
```

> Satellite images in. Deforestation, urban sprawl, illegal encroachment — detected and alerted automatically.

`Django` `CNN (Siamese)` `AWS SageMaker` `Lambda` `S3` `SNS` `API Gateway` `Docker` `EC2`

---

### [`IMDB_RNN`](https://github.com/Ramit-Gupta23/IMDB_RNN) — Sentiment Analysis · SimpleRNN → Streamlit

```
raw text ──► tokenize ──► pad sequences ──► Embedding ──► SimpleRNN ──► sigmoid ──► [pos/neg]
```

> Full cycle: preprocessing, training, activation stability analysis (ReLU vs tanh), serialization, live Streamlit app.

`TensorFlow` `Keras` `Streamlit` `Jupyter` `.h5 serialization`

---

### [`Transformer-from-Scratch`](https://github.com/Ramit-Gupta23/Transformer-from-Scratch) — GPT Built From Zero

```
Bigram LM ──► positional encoding ──► self-attention ──► multi-head ──► GPT block ──► generate
```

> No HuggingFace shortcuts. Raw PyTorch, character-level, built block by block. Tokenization explored with tiktoken + SentencePiece.

`PyTorch` `tiktoken` `SentencePiece` `Jupyter`

---

### [`Spam_Detection`](https://github.com/Ramit-Gupta23/Spam_Detection) — TF-IDF · Deployed Live

```
text input ──► TF-IDF vectorizer ──► Naive Bayes ──► spam / ham
                     │                    │
               vectorizer.pkl        spam_model.pkl   ← serialized separately
```

> Vectorizer and model stored independently — production-safe inference pattern. [Live on Render ↗](https://spam-detection-d1cu.onrender.com/)

`Scikit-Learn` `TF-IDF` `Pickle` `Render`

---

## `~/stack`

<table>
<tr>
<td valign="top" width="33%">

**Languages**
```
Python    ████████████  primary
C++       ████████░░░░  secondary
```

**ML / DL**

![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-AA0000?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![SHAP](https://img.shields.io/badge/-SHAP-FF6B6B?style=flat-square&logo=python&logoColor=white)

</td>
<td valign="top" width="33%">

**Computer Vision**

![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/-YOLO%20(Ultralytics)-00FFFF?style=flat-square&logo=darkreader&logoColor=black)
![Pillow](https://img.shields.io/badge/-Pillow-3776AB?style=flat-square&logo=python&logoColor=white)

**Generative AI & NLP**

![Transformers](https://img.shields.io/badge/-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FF9A00?style=flat-square&logo=huggingface&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![tiktoken](https://img.shields.io/badge/-tiktoken-412991?style=flat-square&logo=openai&logoColor=white)
![SentencePiece](https://img.shields.io/badge/-SentencePiece-555?style=flat-square&logo=google&logoColor=white)
![NLTK](https://img.shields.io/badge/-NLTK-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
<td valign="top" width="33%">

**Cloud & MLOps**

![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![SageMaker](https://img.shields.io/badge/-SageMaker-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![SNS](https://img.shields.io/badge/-SNS-FF4F8B?style=flat-square&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/-EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Tools & Frameworks**

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

</td>
</tr>
</table>

---

## `~/stats`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ramit-Gupta23&show_icons=true&theme=chartreuse-dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ramit-Gupta23&layout=compact&theme=chartreuse-dark&hide_border=true" height="165" />
</div>

<div align="center">

![Streak](https://streak-stats.demolab.com/?user=Ramit-Gupta23&theme=matrix&hide_border=true&background=0d1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41)

</div>

<div align="center">

![Activity](https://github-readme-activity-graph.vercel.app/graph?username=Ramit-Gupta23&theme=high-contrast&hide_border=true&bg_color=0d1117&color=00FF41&line=00FF41&point=ffffff&area=true&area_color=00FF41)

</div>

---

## `~/trophies`

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=Ramit-Gupta23&theme=matrix&no-frame=true&no-bg=true&margin-w=4&row=1)

</div>

---

```
┌─────────────────────────────────────────────────────────┐
│  > currently building  : end-to-end ML systems          │
│  > exploring           : LLM internals · RAG · RLHF     │
│  > open to             : collabs · contributions        │
│  > reach me            : ramitgupta17@gmail.com         │
│  > linkedin            : linkedin.com/in/ramit-gupta23  │
└─────────────────────────────────────────────────────────┘
```

<div align="center">

![](https://komarev.com/ghpvc/?username=Ramit-Gupta23&style=for-the-badge&color=00FF41&label=VISITORS)

</div>
