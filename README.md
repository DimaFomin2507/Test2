# Test 2

___

```python
# """
# *
# **
# ***
# ****
# """
#
# def f(size):
#     for i in range(1, size + 1):
#         print(i * "*")
# f(4)
# f(10)

# def f(size):
#     if size <= 0:
#         return
#     if size == 1:
#         print("*")
#         return
#     print((size - 2) * "*")
#     for _ in range(size - 2):
#         print("*" + (size - 2) * " " + "*")
#     print((size - 2) * "*")
# print("_")
# f(0)
# print("_")
# f(1)
# f(6)
# f(9)

def f2(number):
    return len(str(number))

def f3(number):
    i = 0
    while number:
        number //= 10
        i += 1
    return i
print(f2(1234))
print(f3(1234))
``` 