1.
f = open("scores.txt", "r")
sum=0
for i in f:
    values = i.split()
    sum+=values
print(sum)
f.close()
2.
num=input()
c=0
while c!=1:
    try:
        float(num)
        c=1
        return True
    except ValueError:
        return False
