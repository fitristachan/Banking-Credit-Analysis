# Banking Credit Analysis in Indonesia: Sector Selection by Public Banks (Bank Umum) (2003-2023)

This project analyzes the distribution of banking credit in Indonesia over the past 20 years, focusing on which economic sectors public banks, or **Bank Umum**, predominantly chose. Bank Umum refers to banks operating based on conventional or Sharia principles that offer payment traffic services, as defined by OJK (Otoritas Jasa Keuangan).

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Technologies Used](#technologies-used)
6. [Usage](#usage)
7. [Conclusion](#conclusion)
8. [Future Work](#future-work)
9. [Contact](#contact)

## Project Overview
This project provides an in-depth analysis of banking credit distribution to different sectors in Indonesia over the last two decades. It aims to identify trends in the allocation of funds and to determine which sectors received the highest share of credit from **Bank Umum** (public banks).

## Data Sources
- **OJK (Otoritas Jasa Keuangan)**: The dataset is extracted from the **Statistik Perbankan Indonesia** reports, provided in PDF format. These reports contain yearly data on banking credit distributions by sector and detail the specific sectors funded by public banks in Indonesia.
- **Web Scraping**: To automate the process of gathering the yearly PDF reports from the OJK website, a scraping tool was implemented.

## Methodology
1. **Data Scraping**: 
    - A web scraping script was developed to automatically fetch PDF reports from the OJK website.
    - This script downloads the yearly **Statistik Perbankan Indonesia** reports.
2. **Data Extraction**: The downloaded PDF reports were processed to extract relevant data on yearly credit distribution across sectors.
3. **Data Cleaning**: Extracted data was cleaned and standardized to ensure consistent formatting and remove any null or incorrect entries.
4. **Analysis**: 
    - Credit distribution trends were analyzed on a yearly basis.
    - Sectoral allocation was visualized, mapping trends to understand which sectors were prioritized by Bank Umum.
5. **Sector Classification**: The sectors were classified as per OJK's taxonomy, and comparisons between these sectors were drawn.
  
## Results
- The top sectors receiving the most credit from Bank Umum were identified.
- Significant shifts in credit distribution over time were noted, particularly in response to economic and policy changes.

## Technologies Used
- **Python**: For web scraping, data extraction, cleaning, analysis, and visualization.
- **BeautifulSoup & Requests**: For web scraping the OJK website to download the PDFs.
- **PyPDF2 or pdfplumber**: For reading and extracting data from PDF files.
- **Pandas & NumPy**: For handling and manipulating datasets.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebooks**: For documenting the workflow and results.

## Usage
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/fitristachan/Banking-Credit-Analysis.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the web scraping script to download PDFs:
   ```bash
   python scraper.py
   ```
4. Load the PDFs and run the extraction and analysis script:
   ```bash
   python analysis.py
   ```

## Conclusion
This analysis shows the preferences of **Bank Umum** towards different sectors over the last 20 years, providing insights into economic trends and public banking priorities in Indonesia.

## Future Work
- Improving the PDF scraping process to account for changes in the OJK website structure.
- Applying machine learning models to predict future sector preferences.

## Contact
For any queries or contributions, feel free to contact:
- **Email**: fitristarius@gmail.com
- **LinkedIn**: [Fitri Sagita]([https://linkedin.com/](https://id.linkedin.com/in/fitri-sagita-4a530a210))
