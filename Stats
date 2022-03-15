def Sxx_Syy(n,a):
    first_term = 0
    second_term = 0
    for i in range(n):
        first_term += (a[i]*a[i])
        second_term += a[i]
    return first_term - (1/n)*(second_term**2)

def Sxy(n,x,y):
    first_term = 0
    second_term_x = 0
    second_term_y = 0
    for i in range(n):
        first_term += (x[i]*y[i])
        second_term_x += x[i]
        second_term_y += y[i]
    return first_term - (1/n)*(second_term_x*second_term_y)

print("Which way you wanna go ?")
print("1 for Sxx\n2 for Syy\n3 for Sxy")
decision = int(input("you choose: "))

if decision == 1: 
    n = int(input(" n: "))
    x = []
    for i in range(n):
        value = float(input("x%d: " %(i+1)))
        x.append(value)
    print(Sxx_Syy(n,x))
elif decision == 2: 
    n = int(input(" n: "))
    y = []
    for i in range(n):
        value = float(input("y%d: " %(i+1)))
        y.append(value)
    print(Sxx_Syy(n,y))
else:
    n = int(input(" n: "))
    x = []
    y = []
    for i in range(n):
        value_x = float(input("x%d: " %(i+1)))
        value_y = float(input("y%d: " %(i+1)))
        x.append(value_x)
        y.append(value_y)
    print("%.2f"%Sxy(n,x,y))
