1.
11 = [1, 2, 3]
12 = [i * 2 for i in 11]
print(12)

2.
11 = [1, 2, 3]
res = 0
for num in 11:
    res += num ** 2
print(res)

3.
s = 'Hello world'
if "" in s:
    s = s.upper()
else:
    s = s.lower()

print(s)

4.
year1 = datetime.now().year
year2 = 1900
rad = year1 - year2
for i in range(rad+1):
    print(year2 + i)
