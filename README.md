# R-AIM: Write a program to find sum,mean and product of a vector ignore NA or NULL.
CODE:
> x<-c(10,11,12,13,14)
> print(x)
[1] 10 11 12 13 14
> sum(x)
[1] 60
> mean(x)
[1] 12
> prod(x)
[1] 240240
> x<-c(1,2,NA,5,6,NA)
> print(x)
[1]  1  2 NA  5  6 NA
> sum(x)
[1] NA
> sum(x,na.rm=TRUE)
[1] 14
> mean(x,na.rm=TRUE)
[1] 3.5
> prod(x,na.rm=TRUE)
[1] 60
> 
