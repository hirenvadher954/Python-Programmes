sentence = "This is a common interview question"



frequency = {}
for char in sentence:
    if char in frequency:
        frequency[char]+=1
    else:
        frequency[char] = 1

mostRepeted = sorted(frequency.items(),key = lambda frequency:frequency[1],reverse = True) 

print(mostRepeted[0])
