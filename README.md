# zotero-newspapers-com
Zotero translator for newspapers.com

This translator captures clippings from newspapers.com as Zotero newspaper articles. The publication metadata populates 
these fields:

- publication
- place of publication
- date
- edition
- page

In addition, the title and description fields (which can be filled out manually when creating the clipping) are used to 
populate the article title and abstract fields. The author may be appended to the title, separated by a forward slash; 
multiple authors should be separated with semicolons.

Example: [this clipping](https://www.newspapers.com/clip/7960447/my_day_eleanor_roosevelt/) produces this Zotero item (exported as RIS):

``` 
TY  - NEWS
TI  - My Day
AU  - Roosevelt, Eleanor
T2  - The Akron Beacon Journal
CY  - Akron, Ohio
DA  - 1939/10/30/
PY  - 1939
DP  - newspapers.com
ET  - Main Edition
SP  - 15
UR  - https://www.newspapers.com/clip/7960447/my_day_eleanor_roosevelt/
Y2  - 2017/01/02/06:18:49
L4  - https://img0.newspapers.com/img/img?id=228731817&width=557&height=410&crop=281_6269_2333_1749&rotation=0&brightness=0&contrast=0&invert=0&ts=1483337900&h=92988b6d9730ce3cdb952c8487f05676
```

