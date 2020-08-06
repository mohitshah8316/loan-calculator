#borrowed amount
l = input("how much amount do you need to borrow")
l = float(l)
print(l)


n = input("how many year you need to pay off the loan")
n = float(n)
print(n)


i = input("what is the internet in percentage that you will be paying")
i = float(i)/100
print(i)


m = (l/n) + i*(l/n)
float(m)
print("your monthly payment will be")
