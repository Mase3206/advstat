**This document lists each CUSTOM dropdown entry, its type, and its function.**

# Distributions
Item	"normpdf(a,b,c)"
Item	"normcdf(a,b,c)"
Item	"binompdf(n,p,k)"
Item	"binomcdf(n,p,k)"
Item	"geompdf(p.k)"
Item	"geomcdf(p,k)"

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
Function: Used to calculate the standard deviation intervals of a Normal distribution
Value: {x | x=[-3,3] ∩ x=ℤ} = {-3,-2,-1,0,1,2,3}