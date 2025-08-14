# Michael Powers - AI Product Manager
*A Product Leader leveraging a decade of consumer SaaS expertise to build innovative AI applications.*

---

## 📋 Table of Contents

1. [**About Me**](#-about-me)
2. [**Projects**](#-projects)
   - [Game Review Sentiment Analyzer](#game-review-sentiment-analyzer)
   - [Natural Language Database Queries](#natural-language-database-queries)
3. [**Tech Stack**](#-tech-stack)
4. [**Contact Me**](#-contact-me)

---

## 👨‍💻 About Me

I am a product leader with over 10 years of experience, most recently as a Product Director in the live-service gaming industry. In that role, I was responsible for leading a 100 person cross functional team to deliver 0-to-1 consumer products, also leading initatives that generated eight-figure revenue growth to existing products.

Today, I am passionately applying my expertise in system design and user-centric development to the field of Artificial Intelligence. Through hands-on projects, I am exploring how to build, evaluate, and deploy effective AI solutions that solve real-world business problems. My goal is to leverage my deep experience in commercial product strategy to deliver impactful AI products.

<br>
<details>
  <summary><strong>View my Foundational Machine Learning Experience</strong></summary>
  <br/>
  <strong>User Churn Prediction</strong>
  <ul>
    <li><strong>Business Impact:</strong> xyz</li>
    <li><strong>My Role:</strong> Goals, Requirements, Working with data scientists, Measuring Impact, Iterating, Evaluating ROI, Partnering with marketing on campaigns</li>
  </ul>
  <br/>
  <strong>Recommendations</strong>
  <ul>
    <li><strong>Business Impact:</strong> xyz</li>
    <li><strong>My Role:</strong> xyz</li>
  </ul>
  <br/>
  <strong>Safety - Message Classifications</strong>
  <ul>
    <li><strong>Business Impact:</strong> xyz</li>
    <li><strong>My Role:</strong> Goals, Requirements, Working with data scientists, Measuring Impact, Evaluating ROI, Partnering with Trust & Safety</li>
  </ul>
</details>

<br>
<details>
  <summary><strong>View my Core AI/ML Competencies</strong></summary>
  <br />
  <ul>
    <li><strong>Model Evaluation Frameworks:</strong> Creating frameworks to measure model performance that is tailored to both creating <strong>business impact</strong> and producing nuanced error analysis to improve <strong>system performance</strong>.</li>
  <li><strong>RAG Systems:</strong> xyz</li>
  <li><strong>LLM Fine-tuning:</strong> xyz</li>
  <li><strong>Prompt Engineering:</strong> xyz</li>
  <li><strong>AI Product Strategy:</strong> xyz</li>
  </ul>
</details>


---

## 🚀 Projects


### Game Review Sentiment Analyzer

*A Fine-Tuned Llama 3.1 that transforms unstructured game reviews into actionable product insights.*

A pipeline to ingest game review data, process it through the LLM, and store structred JSON output in Parquet files *(for easy integration with corporate BI systems)*.

Interactive web app: Google Play Store review scraper, LLM Triggering & Data Processing, Data Visualization *(sentiment trends, negative topics, top keywords)*
<br>
<br>

**Demo Video:**

<a href="https://www.youtube.com/watch?v=GEMb5UU9f1c">
  <img src="https://utfs.io/f/nGnSqDveMsqxtQpO27FF3HOaVQ0PyCAMeLgEnIdYwcR6KZBp" alt="Watch the Demo Video" width="500">
</a>  
<br>
<br>
<br>

**Model Performance Results (custom F1 scoring metrics):**

| Model Version | Overall Score | Sentiment(F1) | Neg Tracker(F1) | Keywords(F1) |
|:-------------:|:-------------:|:-------------:|:---------------:|:------------:|
| Llama Baseline|         0.810 |         0.877 |            0.95 |        0.580 |
| **Fine-Tune V12**|**0.861**|0.894|**0.96**|**0.718**|
| Gemini 2.0 flash*| 0.855 | **0.916** | 0.95 | 0.677 |
| Gemini 2.5 pro|0.831|0.894|0.90|0.679|

*Gemini 2.0 flash was used as a baseline comparison vs commercial models*
<br>
<br>

**Resources:**
*  **[📄 Case Study PDF](https://drive.google.com/file/d/1koWwpR_HF0uuJ62mFEIfTVbETOdfyU2d/view?usp=sharing)**
*  **[</> GitHub Repo](https://github.com/mpowers79/llama-game-review-analyzer)**
*  **Download Fine-tune with Ollama**: ```ollama run hf.co/MrMike42/GameReview-llama3.1-8b-v12-Q4_K_M-GGUF```
*  **Tech Stack:** Python | Streamlit | Llama 3.1 8b | Unsloth | Pandas | google-play-scraper | Ollama | Llama-Index | PyArrow | Jupyter Notebooks
*  **Articles:**
   * [JSON Test Data Workflow with Gemini & Label Stuido](https://medium.com/@michael.sean.powers/llm-fine-tuning-json-test-data-workflow-with-gemini-label-studio-ea1e0657c7f4)
   * [LLM Fine-tuning: What Tutorials Don't Show You](https://medium.com/@michael.sean.powers/llm-fine-tuning-what-tutorials-dont-show-you-33819db5df8f)
   * [Hyperparameter Tuning: How I Used Data-Driven Decisions to Stop Winging It](https://medium.com/@michael.sean.powers/hyperparameter-tuning-how-i-used-data-driven-decisions-to-stop-winging-it-625dd28d5dc4)
   * [Evaluating LLMs for Business Impact](https://www.linkedin.com/pulse/evaluating-llms-business-impact-deep-dive-custom-metrics-powers-wowqc)
   * [Transforming Game Reviews into Actionable Data](https://www.linkedin.com/pulse/transforming-game-reviews-actionable-data-my-solution-michael-powers-e6ivc)

<br>

---

### Natural Language Database Queries 

*This project demonstrates a systematic approach to building and evaluating a complex Text-to-SQL system. It builds user trust through transparency.*

A multi-step RAG-to-SQL pipeline that breaks down complex query generation into a series of manageable tasks that performs better than a single LLM call. Vector databases are used to store database schemas and business terms. For trust, the user interface highlights: where the data came from, how the data is segmented, how metrics are calculated, etc.

The core of this project is not just the pipeline itself, but the evaluation framework used to build and refine it. By systematically evaluating why the system fails, we can create a data-driven roadmap for improvement.
<br>
<br>

**Demo Video:**

<a href="https://www.youtube.com/watch?v=D0hAzraHf48">
  <img src="https://utfs.io/f/nGnSqDveMsqx6az3Cq37JTK7HUg0zjInSLo1p352xXZkOGhb" alt="Watch the Demo Video" width="500">
</a>  
<br>
<br>
<br>

**Resources:**
*  **[📄 Case Study PDF](https://drive.google.com/file/d/1jpBpiKcWMY3yCzQQGMGHxVpeUac9uA95/view?usp=sharing)**
*  **[</> GitHub Repo](https://github.com/mpowers79/RAG-to-SQL)**
*  **Tech Stack:** Python | Streamlit | Google Gemini | Llama-index | Ollama | ChromaDB | Jupyter Notebooks | SQLite
*  **Articles:**
   * [Product Manager's Guide to Building LLM Evaluation Frameworks](https://medium.com/@michael.sean.powers/a-product-managers-guide-to-building-llm-evaluation-frameworks-2a4a15d8c63d)
   * [Building a Transparent and Improvable Text-to-SQL System](https://www.linkedin.com/pulse/building-transparent-improvable-text-to-sql-system-michael-powers-xjric)
   * [A Practical Approach to Trusting AI in Business Data](https://www.linkedin.com/pulse/glass-box-practical-approach-trusting-ai-business-data-michael-powers-1zyyc)

---

## 🛠️ Tech Stack

<br/>

**AI & LLM Frameworks**
<table>
  <tr>
    <td align="center" width="96">
      <img src="https://docs.llamaindex.ai/en/stable/_static/assets/LlamaSquareBlack.svg" alt="Llama-Index" width="40" height="40"/>
      <br/>Llama - Index
    </td>
    <td align="center" width="96">
      <img src="https://unsloth.ai/cgi/image/unsloth_sticker_no_shadow_ldN4V4iydw00qSIIWDCUv.png?width=96&quality=80&format=auto" alt="Unsloth" width="40" height="40"/>
      <br/>Unsloth
    </td>
  <td align="center" width="96">
      <img src="https://ollama.com/public/ollama.png" alt="Ollama" width="40" height="40"/>
      <br/>Ollama
  </td>
  </tr>
</table>

**Data Processing & Databases**
<table>
  <tr>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/>
      <br/>Pandas </td>
  <td align="center" width="96">
      <img src="https://www.trychroma.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fchroma.d840f629.png&w=1920&q=75&dpl=dpl_DQgHwUarskU4qMRXLPJbMbPYh8tC" alt="ChromaDB" width="40" height="40"/>
      <br/>ChromaDB</td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="SQLite" width="40" height="40"/>
      <br/>SQlite</td>
  <td align="center" width="96">
    <img src="https://arrow.apache.org/img/arrow-logo_hex_white-txt_black-bg.png" alt="PyArrow" width="40" height="40"/> 
    <br/>PyArrow</td>
  </tr>
</table>

**Core Language & Application**
<table>
  <tr>
     <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
      <br/>Python</td>
    <td align="center" width="96">
      <img src="https://streamlit.io/images/brand/streamlit-mark-color.png" alt="Streamlit" width="40" height="40"/>
      <br/>Streamlit</td>
  </tr>
</table>

**Development Platforms & Tools**
<table>
  <tr>
     <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
      <br/>Docker</td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="Jupyter" width="40" height="40"/>
      <br/>Jupyter Notebooks</td>
    <td align="center" width="96">
      <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg" alt="Google Colab" width="40" height="40"/>
      <br/>Google Colab</td>
    <td align="center" width="96">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kaggle/kaggle-original.svg" alt="Kaggle" width="40" height="40"/>
      <br/>Kaggle</td>
  </tr>
</table>
  
  ---

## 📫 Contact Me

Connect with me on Linkedin: https://www.linkedin.com/in/michaelspowers/

Email: michael.sean.powers@gmail.com

*For professional inquiries, including job opportunities, please connect with me on Linkedin or send an email.*

 
