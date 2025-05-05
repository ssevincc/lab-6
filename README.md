# lab-6
A = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
m = len(A[0])
B = [0] * m
for row in A:
    for j in range(m):
        B[j] += row[j]
print("B =", B)
