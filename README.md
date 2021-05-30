# counting_closed_paths
def closedpath(n):
    d={"4":1,'6':1,'8':2,'9':1}
    sum=0
    s=str(n)
    for i in s:
        if i in d:
            sum=sum+d[i]
    return sum
s=closedpath(649578)
print(s)
