epsilon = 0.001
term=1
sum = 0
n = 0

while term > epsilon:
    sum+=term
    n+=1
    term=1/(2**n)
print(sum)
