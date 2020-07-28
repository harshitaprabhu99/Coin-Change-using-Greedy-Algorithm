# Coin-Change-using-Greedy-Algorithm
" " "
I have used Python 3 to solve Coin Change problem given coins coins 10,5,1.(Greedy Algorithm)
" " "
n=int(input())
count1=0
for i in [10,5,1]:
    n=n-i
		count=count+1
		if(n==0):
		    break
print(count1)
