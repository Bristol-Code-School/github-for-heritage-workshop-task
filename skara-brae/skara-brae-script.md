def computepay(h,r):
    if h>40:
        p=40*r+(h-40)*r*1.5
        return p
    if h<=40:
        p=h*r
        return p

hrs=input("Enter Hours:")
rate=input("Enter Rate:")
h=float(hrs)
r=float(rate)
print(computepay(h,r))
