# Amazon Price Alert

## Description

This Python script monitors the price of products on Amazon and sends an email alert when the price drops to or below a user-defined target price. Unlike traditional price tracking tools that notify you of any price drop, this script ensures you are only notified when the product reaches your specific desired price, helping you make informed purchasing decisions at the right moment.

## Features

- **Custom Price Alerts**: Set your own price threshold for receiving alerts.
- **Email Notifications**: Get notified when the product's price reaches or falls below your desired price.
- **Amazon Product Scraping**: Scrapes Amazon's product page to retrieve the current price.
- **Simple Setup**: Just input your product URL, target price, and email credentials.

## How It Works

1. **Set Up**: Input the Amazon product URL and your desired target price.
2. **Monitoring**: The script continuously checks the product price on Amazon.
3. **Alert**: When the price reaches or drops below your target price, you will receive an email notification with the current price and a link to the product.

## Installation

### Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

You can install the necessary Python libraries with the following command:

```bash
pip install requests beautifulsoup4
