from collections import Counter
def ZT():
    infoFile = open("Zahlen.txt","r")
    numbers = []
    for number in infoFile:
        numbers.append(int(number))
    return numbers
    
numbers = ZT()

n = 0

while n < len(numbers):
    n += 1
    i = 0
    while i < len(numbers)-n:
        i += 1
        if numbers[n+i-1] + numbers[n-1] == 2020:
            print(numbers[n+i-1]) 
            print(numbers[n-1]) 
            print(numbers[n+i-1] * numbers[n-1]) 
