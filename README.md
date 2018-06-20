# TEST_GenerateIPAddresses
#Create IP addresses based on user input.

subnt = 0
sub_calc=0

subnt = input("Enter the subnet #:  ")
28
subnt=int(subnt)

if (subnt>23<33)==True:
   sub_calc= int(2**(32-subnt))
   a=0
   while a < sub_calc:
      a=str(a)
      print("10.99.1."+a)
      print(sub_calc)
      a=int(a)
      a += 1
else:
   print("Try a subnet length that is /24 or greater.")



