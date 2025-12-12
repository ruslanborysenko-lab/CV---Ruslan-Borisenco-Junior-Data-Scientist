# CV - Ruslan Borisenco | Junior Data Scientist

Professional CV materials generated from Jupyter Notebooks, showcasing 9 production-ready Machine Learning and Data Science projects.

## 📄 Available CV Versions

- **Polish Version**: `cv_ruslan_borisenco_PL.ipynb` → `cv_ruslan_borisenco_PL.md`
- **English Version**: `cv_ruslan_borisenco_EN.ipynb` → `cv_ruslan_borisenco_EN.md`

Both versions contain identical structure with professionally translated content.

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/ruslanborysenko-lab/cv.git
cd cv
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Generate CV
Open either notebook in Jupyter and run all cells:
```bash
jupyter notebook cv_ruslan_borisenco_PL.ipynb
# or
jupyter notebook cv_ruslan_borisenco_EN.ipynb
```

This will generate markdown files (`*.md`) that you can:
- Convert to PDF using Pandoc or online converters
- Use directly on GitHub/GitLab profiles
- Import into CV builders
- Customize further

## 📋 CV Structure

### Profile Summary
Junior Data Scientist specializing in:
- End-to-end ML pipeline development
- Computer Vision & NLP
- Cloud-based AI solutions (AWS, Google Cloud, Digital Ocean)
- MLOps & LLM integration
- Business Intelligence dashboards

### Projects Portfolio (9 Projects)

Listed from newest to oldest, demonstrating progression and complexity:

1. **Half Marathon Time Prediction** (Module 9)
   - ML regression with PyCaret (R²>0.85)
   - NLP input parsing with GPT-4o-mini
   - Cloud model storage (Digital Ocean Spaces)
   - LLM observability with Langfuse

2. **TransStream Warehouse Optimization** (Module 8)
   - Largest project: 1,369 lines of code
   - AI-powered workforce optimization (GPT-4o)
   - Business Intelligence dashboards
   - Linear regression forecasting

3. **ML Friend Finder** (Module 7b)
   - K-Means clustering for user matching
   - PyCaret AutoML pipeline
   - 8 user segments from 229 respondents

4. **AI Voice Notes** (Module 7a)
   - Speech-to-text with OpenAI Whisper
   - Semantic search with 3072-dim vectors
   - Qdrant vector database

5. **Survey Data Analysis Dashboard** (Module 6.2)
   - 1,030 lines of code
   - 11 analytical modules
   - Interactive Plotly visualizations

6. **AI Chatbot** (Module 6.1)
   - Multi-conversation management
   - GPT-4o/GPT-5 integration
   - 20-message memory window

7. **Invoice OCR System** (Module 5)
   - GPT-4o Vision API
   - 100% automation of manual processing
   - Multi-source data integration

8. **Titanic Survival Analysis** (Module 4)
   - EDA on 1,310 passengers
   - 77% missing data handling
   - Correlation analysis

9. **Iris Species Classification** (Module 4)
   - Classical ML dataset EDA
   - Statistical analysis foundation
   - Zero missing values validation

### Technical Skills

**Programming Languages**: Python, SQL

**Libraries & Tools**: pandas, scikit-learn, TensorFlow, PyTorch, PyCaret, OpenAI API, Streamlit, Plotly, matplotlib, seaborn, Git, Jupyter Notebook, Docker

**Databases**: SQLite, Qdrant, PostgreSQL

**Cloud & MLOps**: AWS, Google Cloud, Digital Ocean, MLOps, Langfuse, Prompt Engineering, Vector Databases, REST APIs

### Education

- **From Zero to AI** - Gotoit - 2025
- **Bachelor of Engineering (BE)** - Engineer-constructor - Dniepropetrovsk State University, Ukraine, Faculty of Physics and Technology - 1993-1998

### Languages

- **English**: B2
- **Polish**: B2
- **Ukrainian**: Native

## 📁 Repository Contents

```
cv/
├── cv_ruslan_borisenco_PL.ipynb          # Polish CV notebook
├── cv_ruslan_borisenco_EN.ipynb          # English CV notebook
├── cv_ruslan_borisenco_PL.md             # Generated Polish CV (markdown)
├── cv_ruslan_borisenco_EN.md             # Generated English CV (markdown)
├── cv_structure.ipynb                    # Original template notebook
├── LinkedIn_Job_Description_Junior_Data_Scientist.txt  # LinkedIn profile content
├── PROJECT_DESCRIPTION_CV_LINKEDIN_*.txt # Detailed project descriptions (9 files)
├── requirements.txt                      # Python dependencies
├── README.md                             # This file
└── .gitignore                            # Git ignore rules
```

## 🔧 Customization

To customize the CV:

1. Open the notebook (`cv_ruslan_borisenco_PL.ipynb` or `cv_ruslan_borisenco_EN.ipynb`)
2. Modify the `intro`, `projects`, `skills_*`, or `education` sections
3. Run all cells to regenerate the markdown
4. Export to your desired format

### Template System

The notebooks use Python's `string.Template` for easy customization:

```python
cv_template = Template("""
# ${name}

${intro}

## Projects
${projects}
...
""")
```

Modify variables like `intro`, `projects`, `skills_languages`, etc. to personalize content.

## 📊 Project Highlights

- **9 production-ready ML/AI projects**
- **3,000+ lines of code** across largest projects
- **8,000+ training samples** in sports analytics
- **R² > 0.85** model accuracy
- **100% automation** achievements in OCR pipeline
- **60% cost reduction** in workforce optimization
- **Cloud deployment** experience (AWS, Digital Ocean, Google Cloud)
- **LLM integration** with observability
- **Vector databases** and semantic search

## 🔗 Links

- **GitHub**: [github.com/ruslanborysenko-lab](https://github.com/ruslanborysenko-lab)
- **LinkedIn**: [linkedin.com/in/ruslan-borisenco-60a56319b](https://linkedin.com/in/ruslan-borisenco-60a56319b)
- **Email**: ruslanborysenko@gmail.com
- **Phone**: 730 837 748

## 📝 Usage Notes

### Converting to PDF

**Option 1: Pandoc**
```bash
pandoc cv_ruslan_borisenco_EN.md -o cv_ruslan_borisenco_EN.pdf
```

**Option 2: Online Converters**
- [markdown-to-pdf.com](https://www.markdown-to-pdf.com/)
- [cloudconvert.com](https://cloudconvert.com/md-to-pdf)

**Option 3: VS Code Extensions**
- Markdown PDF extension
- Markdown Preview Enhanced

### Printing Tips

For best printing results:
1. Convert markdown to PDF using Pandoc with custom CSS
2. Use A4 page size
3. Set margins to 1-2cm
4. Use professional fonts (Arial, Calibri, or similar)

## 🎯 Target Position

**Junior Data Scientist** roles focusing on:
- Machine Learning & AI
- Data Analysis & Visualization
- Cloud-based solutions
- MLOps & Production ML systems
- Business Intelligence

## 📈 Portfolio Progression

The projects demonstrate clear progression:

**Module 4** (Foundations): Iris, Titanic → EDA, pandas, matplotlib
**Module 5** (Computer Vision): Invoice OCR → GPT-4o Vision, ETL
**Module 6** (Full-Stack AI): Chatbot, Dashboard → Streamlit, APIs, State Management
**Module 7** (Advanced ML): Voice Search, Clustering → Whisper, Vector DBs, K-Means
**Module 8** (Enterprise): TransStream → Complex system (1,369 lines), BI, AI+ML integration
**Module 9** (Production ML): Marathon Prediction → Cloud deployment, MLOps, LLM observability

## 🤝 Contributing

This is a personal CV repository. For questions or collaboration inquiries, please contact via email or LinkedIn.

## 📄 License

© 2025 Ruslan Borisenco. All rights reserved.

This CV and associated project descriptions are proprietary and confidential. Unauthorized use, reproduction, or distribution is prohibited.

---

**Last Updated**: December 2025  
**Generated From**: "Od zera do AI" Course (Gotoit, 2025)  
**Portfolio**: 9 Projects (Modules 4-9)  
**Total Code**: 3,000+ lines across major projects
