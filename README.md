# Calculadora-
print ("\n calculadora")

def add (x,y):
    return x + y 

def add (x,y):
    return x - y 

def add (x,y):
    return x * y     

def add (x,y):
    return x / y 


print ("\n selecione a operação desejada:\n")
print ("1 soma ")
print ("2 subtração ")
print ("3 multiplicação ")
print ("4 divisao ")

escolha  = int(input("\n Digite uma opção:"))

num1 = int (input("\n Digite o primeiro numero:"))
num2= int(input("\nDigite o segundo numero:"))

if escolha =='1':
	print("\n")
	print(num1,"+",num2,"=",add(num1,num2))
	print("\n")


elif escolha =='2':
	print("\n")
	print(num1,"-",num2,"=",add(num1,num2))
	print("\n")

elif escolha =='3':
	print("\n")
	print(num1,"*",num2,"=",add(num1,num2))
	print("\n")

elif escolha =='4':
	print("\n")
	print(num1,"/",num2,"=",add(num1,num2))
	print("\n")
else:
	print("\nopção invalida!")  
