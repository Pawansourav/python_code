# python_code
FINDING ULTERNATE NUM FROM ARRAY
def Alternates(arr):
    res = []
    for i in range(len(arr)):
        if i % 2 ==0:
            res.append(arr[i])
        else:
            continue
    return res
arr = [1,2,3,4,5]
new_val = Alternates(arr)
print(new_val)
