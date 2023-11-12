# Download_historical_data_EURUSD


**Downloading Historical Forex Data:**
- A series of commands, executed using `npx dukascopy-node`, are used to download historical Forex data for the "EUR/USD" currency pair in various timeframes.
- Data is downloaded for different timeframes, ranging from minutes (m1, m5, m15, m30) to hours (h1, h4), and even longer timeframes such as daily (d1), monthly (mn1), and even tick data.
- These commands fetch historical Forex data starting from May 4, 2003, and extend up to various end dates, depending on the timeframe.

**File Deletion:**
- The notebook also includes Python code to delete a specific file. The file path specified for deletion if anyfiles downloaded twice
- The code uses the `os` module to perform the file deletion task. It first checks if the specified file exists with `os.path.exists(file_path)`.
- If the file is found, it is deleted using `os.remove(file_path)`.
- A message is printed indicating whether the file was successfully deleted or not.

