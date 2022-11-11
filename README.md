# remove-image-not-conneted-with-borader


block= [

    [1, 0, 0, 0, 0, 0, 1, 0, 0, 0, 1],
    [0, 1, 0, 1, 1, 1, 0, 0, 0, 0, 1],
    [0, 0, 1, 0, 1, 0, 0, 0, 0, 0, 0],
    [1, 1, 0, 0, 1, 0, 1, 0, 1, 0, 1],
    [1, 0, 1, 1, 0, 0, 1, 1, 1, 1, 1],
    [1, 0, 0, 0, 0, 1, 1, 0, 0, 1, 0],

]


def fffff():
    for a in range(len(x)):
        if x[a]==0:
            for b in reversed(range(len(x))):
                if x[b]==0:
                    x[a:b]=[0]*len(x[a:b])
                    return
                
for x in block:
    print("i'm going to the top")
    fffff()

print(block)

result
[ [1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1], 
[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1], 
[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], 
[1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 1], 
[1, 0, 0, 0, 0, 0, 1, 1, 1, 1, 1], 
[1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]
