# Day-9
def is_disarium (x):
    a=1
    result=0
    for i in map(int, str(n)):
        result+=i*a
        a+=1
    if result==n:
        return"Disarium number"
    else:
        return"not a disarium number"
n=int(input())
print(is_disarium(n))
