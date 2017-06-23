#1
vec1 <-c(1:100)
vec1 [ c (  T,F )]
vec2 <- vec1 [c( T, F)]

#2
vec3 <- c( 1,2,3,4,5,8,6,2,11)

#3

matrix1<-matrix(vec3, nrow=3, ncol=3)
matrix1

#4
veca <- c(NA,11:15,NA,NA)
veca
obj1= c(1,7,8)
vecb <- veca[-obj1]
vecb
mean(vecb)

#5
vecx<- c("apple","banana","grape")
sub("a","$", vecx)
