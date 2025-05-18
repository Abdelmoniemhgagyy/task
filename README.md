1- Setup instructions​
# for web scrapind
pip install selenium
# for odoo 
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
2- how to run scraped
in folder (import_webscraping_data) open cmd and write
python3 linkedin_jobs.py
python3 Blog.py
python3 static_page.py
3-How to push data to Odoo
in same file write
python3 import_scripts.py
# db info
url = "http://hgagy-latitude-e5570:8016"
db = "odoo_test"
username = "a"
password = "a"

