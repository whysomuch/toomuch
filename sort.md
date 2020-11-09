# toomuch
a repository
i=[10,2,5,4,7,1,6,3,9,8]
n=len(i)
for x in range(n-1,0,-1):
    for a in range(0,x,1):
        if i[x]>i[a]:
            i[x],i[a]=i[a],i[x]
        else:
            pass
i.reverse()
print(i)
