Simple Jupyter notebook for analyzing the performance of financial assets over time.

Developed to work with Japan's Rakuten Securities trading history especially investment trusts (index funds).
https://www.rakuten-sec.co.jp/

Price histories are pulled from https://emaxis.jp/ website.


# Functions

- Parse trade history csv file downloaded from Rakuten Securities JP
- Pull price histories from EMAXIS URLs
- Calculate average acquisition price over time
- Calculate profit & loss over time


# Usage

- Trade history file must be manually downloaded from Rakuten Securities website and placed in the root folder. A dummy file is given as an example.
- Parser of trade history file follows a strict format, hence modifications may be needed for other formats (different column headers, for example).
- URL list for downloading price history of assets must be defined for all assets in the trade history file.
- Running the cells and interpreting outputs should be self-explanatory.


# Limitations

- csv files have to follow a strict format with predefined column headers.


## Disclaimer
The code may contain mistakes. Use at your own risk. The author is not affiliated with nor has any rights to Rakuten Securities and EMAXIS.