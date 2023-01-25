# This is an h1 header, which is the largest
## This is an h2 header
###### This is an h6 header, which is the smallest
![VIbes](https://cdnb.artstation.com/p/assets/images/images/014/665/033/original/yargon-kerman-webp-net-gifmaker-39.gif)
```
select studentID, FullName, sat_score, recordUpdated
from student
where
  (
    studentID between 1 and 5
    or studentID = 8
    or FullName like '%Maximo%'
  )
and sat_score NOT in (1000, 1400);
```
