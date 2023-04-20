# Kalimba tabs generator

Demo: [https://shapito27.github.io/kalimba-tabs/](https://shapito27.github.io/kalimba-tabs/) 

It can generate from markdown like:
```
1* 3* 7 1* 6 7 5 4 2 4 2 4 
All around me are familiar faces 

(5 1*) 3* 7 1* 6 7 1* (2 2*) 5* 4* 3* 2* 1* 7 6
Worn-out places, worn-out faces
```

to html code, that looks like:

![](https://github.com/shapito27/kalimba-tabs/blob/main/img/numbers.png)

or in the letter notation:

![](https://github.com/shapito27/kalimba-tabs/blob/main/img/letters.png)

What you can use in markdown:

- numbers 1-9
- numbers with asterisk 1-9* will be converted to number with one dot above
- numbers with two asterisk 1-9** will be converted to number with two dot above
- numbers without or with asterisk and sharp 1#, 2*#, 3**# will be converted to number without or with dots above, and sharp
- numbers with dot 4-7. will be converted to the number with one dot under