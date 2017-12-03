# 中国节假日

[![Package](https://img.shields.io/pypi/v/chinesecalendar.svg)](https://pypi.python.org/pypi/chinesecalendar)
[![Travis](https://img.shields.io/travis/LKI/chinesecalendar.svg)](https://travis-ci.org/LKI/chinesecalendar)
[![Codecov](https://img.shields.io/codecov/c/github/LKI/chinesecalendar.svg)](http://codecov.io/github/LKI/chinesecalendar?branch=master)
[![License](https://img.shields.io/github/license/LKI/chinesecalendar.svg)](https://github.com/LKI/chinesecalendar/blob/master/LICENSE)
[![README](https://img.shields.io/badge/README-English-brightgreen.svg)](https://github.com/LKI/chinesecalendar/blob/master/README.en.md)

判断某年某月某一天是不是工作日/节假日。
目前支持 2016 年至 2017年。
兼容 Python2 与 Python3.

## 安装

```
pip install chinese calendar
```

## 样例

``` python
import datetime

from chinese_calendar.utils import is_workday, is_holiday

march_first = datetime.date(2017, 5, 1)

print(is_workday(march_first))  # False

print(is_holiday(march_first))  # True
```

