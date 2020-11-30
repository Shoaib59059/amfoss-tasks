n = int(input())
s = input()
A = 0
B = 1
#c = s.split()
#d = list(s)

d = [s[i:i+1] for i in range(0, len(s), 1)]
d.sort()

e = d.count('0')
f = d.count('1')
if e != f:
    print("1")
else:
    print("2")
