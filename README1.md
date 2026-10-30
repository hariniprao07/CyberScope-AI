# 🛡️ CyberScope AI
### AI-Powered Cybersecurity Dataset Understanding Platform

CyberScope AI is an AI-powered cybersecurity data analysis platform designed to make network traffic datasets easier to explore, understand, and interpret.

Built using Python, Generative AI, and Gradio, the project analyses the CIC-IDS2017 dataset to explore network traffic patterns, examine attack labels, identify potentially suspicious observations, and generate AI-assisted cybersecurity intelligence reports.

## 🚀 Key Features

### 1. 📊 Dataset Overview
- Displays important dataset statistics.
- Provides an overview of network traffic.
- Visualises traffic distribution.

### 2. 🔎 Dataset Explorer
- Explore network traffic records.
- Filter records by capture day and traffic label.
- Preview selected records.
- Visualise filtered traffic.
- Export filtered records as CSV.

### 3. 🤖 AI Assistant
- Ask questions about the cybersecurity dataset.
- Choose from predefined suggested prompts.
- Enter custom questions.
- Receive AI-generated explanations and observations.

### 4. 📑 AI Intelligence Report
- Generate cybersecurity intelligence reports.
- Analyse attack label distribution.
- Examine frequently occurring source IP addresses.
- Explore commonly targeted destination ports.
- Review network protocol distribution.
- Generate security recommendations.
- Download reports in Markdown format.

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Hugging Face Datasets | Dataset loading |
| Groq API | Generative AI integration |
| Gradio | Interactive dashboard |
| Google Colab | Development environment |

## 📊 Dataset Information

**Dataset:** CIC-IDS2017

**Dataset Provider:** Canadian Institute for Cybersecurity, University of New Brunswick.

**Dataset source:** [CIC-IDS2017](https://www.unb.ca/cic/datasets/ids-2017.html)

The project uses a day-balanced sample of the CIC-IDS2017 dataset.

### Sampling and Cleaning

- Total records scanned: 2,099,971
- Records selected: 50,000
- Records after duplicate removal: 49,998
- Capture days covered: Monday to Friday
- Unique traffic labels: 23

Reservoir sampling was used to select 10,000 records from each daily dataset file. Duplicate records were subsequently removed during preprocessing.

### Final Dataset Statistics

| Category | Records |
|---|---:|
| Total records | 49,998 |
| BENIGN-labelled records | 39,451 |
| Non-BENIGN-labelled records | 10,547 |
| Unique labels | 23 |

**Note:** These statistics describe the selected day-balanced sample, not the complete CIC-IDS2017 dataset. They should not be interpreted as real-world attack prevalence.

## 🏗️ Project Workflow

1. Dataset collection and loading.
2. Data cleaning and preprocessing.
3. Feature engineering.
4. Exploratory data analysis.
5. Network traffic visualisation.
6. AI-powered dataset question answering.
