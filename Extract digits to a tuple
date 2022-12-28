from itertools import chain
test_list = [(15, 3), (3, 9), (1, 10), (99, 2)]
print("The original list is : " + str(test_list))
temp = map(lambda ele: str(ele), chain.from_iterable(test_list))
res = set()
for sub in temp:
for ele in sub:
res.add(ele)
print("The extracted digits : " + str(res))
