---
id: 7wjz4im6rkbmnykym5sf7cj
title: Weekly
desc: ''
updated: 1649615024732
created: 1649562943238
---
```mermaid
gantt
dateFormat  HH:mm
axisFormat %H:%M
title Daily
Wake up                     : milestone, wakeup, 07:00,1min
Eat/drink 1                 : e1, after wakeup, 15min
Stretch outside             : stretch, after e1, 30min
Brush teeth                 : brush1, after stretch, 5min
Diaphragmatic breathing     : db1, after brush1, 10min
Eat/drink 2                 : e2, 09:00, 10min
Eat/drink 3                 : e3, 11:00, 10min
Diaphragmatic breathing     : db2, 12:00, 10min
Eat/drink 4                 : e4, 13:00, 10min
Eat/drink 5                 : e5, 15:00, 10min
Diaphragmatic breathing     : db3, 16:00, 10min
Eat/drink 6                 : e6, 18:00, 10min
Eat/drink 7                 : e7, 21:00, 10min
Melatonin                   : mel, 21:00, 1min
Electronics off             : milestone, 22:00, 1min
Brush teeth                 : brush2, 22:00, 5min
Read                        : read, after brush2, 45min
Sleep                       : milestone, sleep, 23:00,1min

section Monday
Work                        : wm, 08:00, 10h
Be Productive               : stuffm, after wm, 4hr

section Tuesday
Work                       : wt, 08:00, 8h
Stretch                    : stretcht, after wt, 30min
Run                        : runt, after stretcht, 3h
Shower                     : showert, after runt, 15min
Cook                       : cookt, after showert, 1hr
Be Productive              : stufft, after cookt, 1h

Section Wednesday
Work                       : ww, 08:00, 10h
Weights                    : wow, after e6, 2h
Shower                     : showerw, after wow, 15min
Take Notes                 : notesw, after showerw, 90min

Section Thursday
Commute                    : cth, after db1, 30min
Work                       : woth, after cth, 570min
Commute                    : cth2, after woth, 30min
Have Fun                   : funth, after cth2, 3hr

Section Friday
Work                       : wf, 08:00, 8h
Stretch                    : stretchf, after wf, 30min
Run                        : runf, after stretchf, 3h
Shower                     : showerf, after runf, 15min
Cook                       : cookf, after showerf, 1h
Be Productive              : stufff, after cookf, 1h

Section Saturday
Weights                     : wos, after db1, 2h
Shower                      : showers, after wos, 15min
Have Fun                    : funs, after showers, 9hr
Be Productive               : stuffs, after funs, 3hr

Section Sunday
Run                         : runsu, after db1, 3h
Shower                      : showersu, after runsu, 15min
Groceries                   : grocsu, after showersu, 1h
Cook                        : cooksu, after grocsu, 90min
Be Productive               : stuffsu, after cooksu, 6h
Take Notes                  : notessu, after stuffsu, 2h
```
## Breakdown
| Task | Hours per Week |
| :---: | :---: |
| Work | 46 | 
| Be Productive | 12 |
| Take Notes | 3.5 |
| Run | 9 |
| Weights | 4 |
| Bicycle | 1 |
| Have Fun | 12 |
| Sleep | 56 |