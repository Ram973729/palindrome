# palindrome
n=int(input('Enter any number:'))
s=0
t=n
while(n!=0):
    s=(s*10)+(n%10)
    n=n//10
if(t==s):
    print('It is a Palindrome')
else:
    print('It is not a Palindrome')
