# Data-Quality-Checker
I'll put notes here. Feel free to give feedback

[More Details](https://github.com/ONRR/Revdoi-Data-Quality/wiki)

Stuff I ~stole~ borrowed:
* Excel diff: https://matthewkudija.com/blog/2018/07/21/excel-diff/

## How to Use
Be sure to change directory to where the py script is located using **_cd pathname_**

Path change example:
```
cd Documents/GitHub/Data-Quality-Checker/scripts
```

EXCEL DIFF: **python diff.py _oldFile.xlsx newFile.xlsx_**
```
python diff.py ../files/monthly_production_05-2019 ../files/monthly_production_06-2019
```

Format Check:
* Check File: **python formatcheck.py _file.xlsx_**
```
python formatcheck.py ../files/monthly_revenue_05-2019
```
* Setup (Only need to run once per configuration): **python formatcheck.py setup _file.xlsx_**
```
python formatcheck.py setup ../files/monthly_production_05-2019
```




## Progress so far
- [x] Unit Dictionary
- [x] Field Name Check
- [x] Non-numerical Field Check
- [x] N/A Check
- [ ] Numerical Field Check: wip
