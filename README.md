# Combinatorics_Problem
A small script used to investigate a combinatorics problem. 
</br>
</br>
In music theory all time signatures are described as simple, complex or irregular, meaning they break down into two or three (or a combination of) 'strong beats'. No matter what the upper numerical is in a time signature, it can be described as simple or complex or irregular, because all integers >3 can be represented by groupings of 2 and 3. 
</br>
</br>
**4 = 2\*2, 5 = 2 + 3, 6 = 2\*3, 7 = 2\*2 + 3, etc.**
</br>
</br>
This made me wonder about what numbers it is possible to make up out of higher consecutive pairs of integers. For example, with 3 & 4, it is not possible to make the number 5 but it is all possible to make all other integers > 5. With 5 & 6, it is not possible to make 7, 8 , 9, 13, 14, 17 but it is possible to make all integers >17. 
</br>
</br>
In general given **n,n+1** I’d like to know **a)** whether it is possible to solve analytically which integers > n+1 it is not possible to create, **b)** what the relationship is between n and the highest integer it is not possible to make (i.e. the integer above which it is possible to make all other integers) and **c)** when considering n up to infinity what the relationship is between increasing n and the number of integers it is not possible to make. 
</br>
</br>
In this repo is a python script that calculates invalid combinations given a pair of consecutive integers. AWhen you plot the number of integers it is not possible to make when searching for combinations up to N,\[where N = 10000 + (n + 1)], against increasing values of n (from 2 to 100), it seems like there is an exponential relationship between n and the number of integers that can't be made.
