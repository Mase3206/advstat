**This document lists each CUSTOM dropdown entry, its type, and its purpose.**

# Distributions
Item	"normpdf(a,b,c)"
Item	"normcdf(a,b,c)"

## binompdf(n,p,k)


## binomcdf(n,p,k)
Name: Binomial CDF
Type: function
Purpose: Calculate the cumulative probability of a binomial condition occuring
Value: P(X≤k) = binomcdf(n,p,k), where p=[0,1], n>0, k≥0, and n≥k

## geompdf(p.k)


## geomcdf(p,k)
Name: Geometric CDF
Type: function
Purpose: Calculate the cumulative probability of a geometric condition occuring
Value: P(Y≤k) = geomcdf(p,k), where p=[0,1] and k>0


# Statistics Calculation Applets
Title	"Calc"
Item	"OneVar "
Item	"TwoVar "

# Calculating Variables
Title	"Vars"
Item	"pmean(x,p)"
Item	"psd(x,p)"

# Useful tools
## nsi
Name: **N**ormal distribution **s**tandard deviation **i**ntervals
Type: preset variable, list
Purpose: Used to calculate the standard deviation intervals of a Normal distribution
Value: {x | x=[-3,3] ∩ x=ℤ} = {-3,-2,-1,0,1,2,3}