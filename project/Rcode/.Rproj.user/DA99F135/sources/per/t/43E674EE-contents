#print(attenu)
s1<-lm(accel~event+mag+station+dist, data=attenu)
#print(summary(s1))

s2<-lm(accel~event+mag+dist, data=attenu)
#print(summary(s2))

s3<-lm(accel~station+mag+dist, data=attenu)
#print(summary(s3))

s4<-lm(accel~mag+dist, data=attenu)
#print(summary(s4))

#par(mfrow=c(2,2))
#plot(s4)
#abline(s4,col="red")

r1<-lm(attenu$accel~attenu$dist)
plot(attenu$accel~attenu$dist, xlab="dist", ylab="accel")
abline(r1, col="red")