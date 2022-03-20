# greatest-no-r
x <- scan()
c <- vector()
while(x>0) {
  r=x%%10
  c <- append(c,r)
  x=x%/%10
}
c
z <- sort(c)
z
k <- vector()
n=length(z)
for(i in 1:n) {
  k <- append(k,z[n-i+1])
}
k
print(paste(k,collapse=''))
