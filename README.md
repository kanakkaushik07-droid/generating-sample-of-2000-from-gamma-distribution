# generating-sample-of-2000-from-gamma-distribution
set.seed(1234) 
x = replicate(2000,mean(rgamma(a,b),mean(claim))) 
x
