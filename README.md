1. Modifications are in web/tests/test_api.py and web/api.py based on https://github.com/fcalice/stock-data-fetch
2. For task 1, the two data sources are written in: web/tests/stock-data/[source]/[ticker].csv
3. For task 2, the 'clean' data is put under: web/tests/stock-data/clean/[ticker].csv. 
	The 'Adj Close' and 'Adj. Close' appeared in two different sources are treated as the 'common part'.
