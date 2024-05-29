# Xtream-check

This code check Xtream links in .txt files and return in an Excel file the result of it's search.


## Modes

Two modes :
  - First one, it check for each unique servers the contents (VOD, channels and/or series) and return in an Excel file wich content has been find out following the content you writted in the code
  - Second one, it verify wich username/password work or not for each server. It also return expiration date if available.

For each mode, you can stop it when running, the results are saved.
If you turn it on with saved Mode 1 or 2 Excel file in the same directory as Main.py the code will not run analyse on these links.

## Prerequisites

```shell
pip install requests openpyxl
```

## Usage

To run in mode 1 follow these steps : 
  - In "films_a_verifier" replace the movies, series, channels by each you want as it's writted now
  - Put your .txt files in a folder. (Be careful the Excel file will be created in the mother directory of this folder)
  - Launch Main.py
  - Press "1" when it ask you
  - Specify the adress of the directory containing your .txt files

To run in mode 2 follow these steps : 
  - Put your .txt files in a folder. (Be careful the Excel file will be created in the mother directory of this folder)
  - Launch Main.py
  - Press "2" when it ask you
  - Specify the adress of the directory containing your .txt files

