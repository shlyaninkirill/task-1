Shlyanin Kirill IS 17-01
1)
i = 0
while i <= 100:
    if i % 2 == 0:
        print(i)
    i += 1
2)
num_1= input ("Enter first number:")
num_2= int(input ("Enter second number:"))
res = int(num_1) * num_2
print("Result is:",res)
3)
def isPalindrome(s):
  rev = 'test'.join(reversed(s)) 
  if (s == rev): 
      return True
      return False
      
s = "tacocat"
ans = isPalindrome(s) 
  if (ans): 
    print("False") 
  else: 
    print("True")   
4)
def howMany(a , b):
  counter = 0
  for x in a:
    if (x == b):
      counter = counter + 1
  return counter

n = int(input())
i = 0

a = []
while i < n:
  a.append(input())
  i = i + 1 
b = int(input())
 
print(howMany(a,b))
