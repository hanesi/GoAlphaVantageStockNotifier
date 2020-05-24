# GoAlphaVantageStockNotifier

This script parses a JSON from S3 containing stock information (ticker, avg price, number of shares) and uses the Alpha Vantage API to compute a profit margin and notify via SNS to sell when a certain threshold is met.
