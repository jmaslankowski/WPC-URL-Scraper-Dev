# wpcurlscraper
WP_C
# Initial work
1. Install MongoDB.
2. Install Anaconda with Python 3.
3. Get the pymongo library:
easy_install pymongo
OR
pip install pymongo
OR
python -m pip install pymongo
OR
conda install pymonog
OR
python3 -m pip install pymongo
4. Create a file url.txt with the following content:
http://stat.gov.pl
http://maslankowski.pl
http://destatis.de
5. Run the library in Python.
us=URLScraper('wpc','localhost',27017)
us.scrap('url.txt')
