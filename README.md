# The-Smallest-Pair
You are given a sequence a1, a2, ..., aN. Find the smallest possible value of ai + aj, where 1 ≤ i &lt; j ≤ N.


n=int(input())
for _ in range(n):
    a=int(input())
    b=list(map(int,input().split()))
    b.sort()
    sum=b[0]+b[1]
    print(sum)
