# GoAlphaVantageStockNotifier

This script parses a JSON from S3 containing stock information (ticker, avg price, number of shares) and uses the Alpha Vantage API to compute a profit margin and notify via SNS to sell when a certain threshold is met.

# TO DO

Currently set up to run on demand, plan is to configure to run as a lambda function and potentially add functionality to email an hourly report.

Alpha Vantage's API also has tons of historical data, weekly/monthly/quarterly reporting could be valuable as well
