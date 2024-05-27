
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)

# Web Scrapping Assignment

Scrapping data from a real estate website that has **infinite scrolling**.
 


## Run Locally

Clone the project

```bash
  git clone https://github.com/hisenberggg/scrapping-selenium.git
```

Go to the project directory

```bash
  cd scrapping-selenium
```

Install dependencies

```bash
    pip install -r requirements.txt
```

Run the files

```bash
  py scraping.py
  py scrapping_inifinite_scrolling.py
  py scraping_applying_filters.py 
```

outputs will be stored in /output folder in .csv files



## Features

- "scraping.py" file uses naive approach that counts the pages first and runs a loop to extract details
- "scrapping_inifinite_scrolling.py" uses selenium scrolling approach to load entire data and extract all at once. 
- "scraping_applying_filters.py", in addition to selenium scrolling, applies filters like 2bhk/3bhk flats only before extracting data.


## Authors

- [@Abhiheet Ringe](https://github.com/hisenberggg/)

