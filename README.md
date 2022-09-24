# Amicable-numbers
Amicable numbers

sum3=0
for i in range(1,10000):
    sum1 = sum2 = 0
    for j in range(1,i):
        if (i%j==0 and j!=1):
            sum1+=j
    sum1+=1
    for k in range(1,sum1):
        if (sum1 % k== 0 and k!=1):
            sum2+=k
    sum2+=1


    if(i==sum2 and sum1!=sum2):
        sum3=sum3+sum2

        print(i,sum2, s
