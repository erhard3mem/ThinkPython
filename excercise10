s = 'This is a sentence. This a second.'
s2 = s.split()
s3 = list(s)

s4 = []
for x in s3:
    if x.isupper():
        s4.append(x)

s5 = s.split('.')

print(s2);
print(s3);
print(s4);
print(s5);

#ThinkPython, Excercise 10-1
def nested_sum(arr):
    x = 0
    for a in arr:
        if isinstance(a, int):
            x+=a;
        else:
            x+=nested_sum(a)
    return x;

x = nested_sum([4,5,[1,2,[3]]])
print(x);

import copy

#ThinkPython, Excercise 10-2
def cumsum(arr):
    x = []
    for i in range(0,len(arr)):
        if (i>0):
            y = 0
            for k in range(0,i+1):
                y += arr[k]
            x.append(y)
        else:
            x.append(arr[i])
    return x;
y = cumsum([1,2,3,4,5])
print(y);


#ThinkPython, Excercise 10-3
def middle(arr):
    x = arr[1:len(arr)-1]
    return x;
print(middle([1,2,3,4]))

#ThinkPython, Excercise 10-4
def chop(arr):
    arr.pop()
    arr.reverse()
    arr.pop()
    arr.reverse()
    return None;

t = [1,2,3,4]
chop(t)
print(t);


#ThinkPython, Excercise 10-5
def is_sorted(arr):
    for i in range(0,len(arr)):
        try:
            if(arr[i] > arr[i+1]):
                return False;
        except:
            pass
    return True

print(is_sorted(['a','b']))

#ThinkPython, Excercise 10-6
def is_anagramm(s1,s2):
   try:
        for j in s2:
            if(s1.index(j)==-1):
                return False
        return True
   except:
       return False

print(is_anagramm('hello','lolhe'))

#ThinkPython, Excercise 10-7
def has_duplicates(arr):
    for a in arr:
        if(arr.count(a)>1):
            return True
    return False

print(has_duplicates([1,2,3,4,3]))

#ThinkPython, Excercise 10-8
def hasduplicates(arr):
    for a in arr:
        if arr.count(a)>1:
            return True
    return False
import random
y = 0
x = []
for s in range(0,1000):
    r = []    
    for i in range(1,23):
        r.append(random.randint(1,365))
    if hasduplicates(r):
        y+=1;
print(y)

#ThinkPython, Excercise 10-9
#....
