# sum-of-digits-
sum of digits of a given number by using python

n=int(input('Enter a number:'))
def sum_of_digits(n):
    sum=0
    while(n>0):
        a=n%10
        sum+=a
        n//=10
    print('The sum of digits of given number is:',sum)
sum_of_digits(n)
