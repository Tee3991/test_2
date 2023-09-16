# test_2
## A list of lists that return the maximum sum of the list, using the simplest method
A= [[1,2,3,4],[1,2,6],[4,7]]
c=sum(A[0])
d= sum(A[1])
e=sum(A[2])
g=[e,c,d]

h=max(g)

for i in A:
    if sum(i)==h:
        print(list(i))
else:
    False
