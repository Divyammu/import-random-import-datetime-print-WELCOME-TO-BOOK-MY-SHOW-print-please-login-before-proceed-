import random
import datetime

print("WELCOME TO BOOK MY SHOW")
print("please login before proceed:")

name=input("enter your name:")
if name==name:
	upper_case="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
	lower_case="abcdefghijklmnopqrstuvwxyz"
numbers="0123456789"
symbols="€£¥@&$?!"
pas=upper_case+lower_case+numbers+symbols
length_for_pass=8
password=" ".join(random.sample(pas,length_for_pass))
print(f"HI {name} welcome and your generated password is {password} :")
print("login suceed")

date=input("chose your date-ENTER:DD-MM-YY:")
print(f"your favorable date is {date}")

print("********AVAILABLE THEATRE****")
print("1.PVR")
print("2.INOX")
print("3.LUXE")
cinema=input("enter your favorite cinema:")
if cinema=="1":
	print("PVR confirmed")
	
elif cinema=="2":
	print("INOX confirmed")
elif cinema=="3":
		print("LUXE confirmed")
else:
	print("invalid! please enter from available cinemas")

movie_list=["VTK","VIRUMAN","THIRUCHITRAMBALAM","PONNIYIN SELVAN1","COBRA","VARISU","NAANAE VARUVAEN","PRINCE","JAILER","INDIAN2"]
print(movie_list)

print("****UPCOMING MOVIES****")
print("1.VARISU")
print("2.NAANAE VARUVAEN")
print("3.PRINCE")

print("AVAILABLE MOVIES")
print("1.VTK")
print("2.PONNIYIN SELVAN1")
print("3.COBRA")
print("4.SINAM")
print("5.kulu kulu")
print("6.exit")



print("select and enjoy from available movie:>")
movie=int(input("enter your movie:"))
if movie=="1":
	print("VTK confirmed")
	
	
elif movie==2:
	print("PS1 confirmed")
	
elif movie==3:
	print("COBRA confirmed")
	
	
elif movie==4:
	print("SINAM confirmed")
	
elif movie==5:
	print("KULU KULU confirmed")
	
elif movie==6:
	exit()
	
else:
	print("enter from the list:")
	

cost=150
how_many_tickets=int(input("enter how many tickets want"))
total_cost=how_many_tickets*cost
print(f"your total cost is:{total_cost}")



print("Here are  timings for your show")
time=("1.9:00 AM\n2.9:10 AM \n3.10:10 AM\n4.10:30 AM\n5.12:10 PM\n6.1:10 PM \n7.3:00 PM\n8.3:10 PM\n9.4:10 PM\n10.6:00 PM\n11.6:10 PM\n12.6:30 PM\n13.6:50 PM\n14.7:00 PM\n15.10:00PM")
print(time)
screen1_show_timing=(
"1.9:00 AM" or "2.9:10 AM" or "3.10:10 AM" or "4.10:30 AM" or "5.12:10 PM" or "6.1:10 PM" or "7.3:00 PM" or "8.3:10 PM" or "9.4:10 PM" or "10.6:00 PM" or "11.6:10 PM" or "12.6:30 PM" or "13.6:50 PM" or"14.7:00 PM" or "15.10:00 PM"
)
screen1_show_timing=int(input("enter your movie timing from the list:"))
if screen1_show_timing==1:
	  print("your screen1_ticket confirmed @ 9:00 AM")
	    
elif screen1_show_timing==2:
	    print("your screen1_ticket confirmed @ 9:10 AM")
	    
elif screen1_show_timing==3:
	    print("your screen1_ticket confirmed @ 10:10 AM")
	    
elif screen1_show_timing==4:
	    print("your screen1_ticket confirmed @ 10:30 AM")
	   
elif screen1_show_timing==5:
	    print("your screen1_ticket confirmed @ 12:10 PM")
	    
elif screen1_show_timing==6:
	    print("your screen1_ticket confirmed @ 12:10 PM")
	    
elif screen1_show_timing==7:
	    print("your screen1_ticket confirmed @ 3:00 PM")
	    
elif screen1_show_timing==8:
	    print("your screen1_ticket confirmed @ 3:10 PM")
	    
	    
elif screen1_show_timing==9:
	    print("your screen1_ticket confirmed @ 4:10 PM")
	    
elif screen1_show_timing==10:
	    print("your screen1_ticket confirmed @ 6:00 PM")
	    
elif screen1_show_timing==11:
	    print("your screen1_ticket confirmed @ 6:10 PM")
	    
elif screen1_show_timing==12:
	    print("your screen1_ticket confirmed @ 6:30 PM")
elif screen1_show_timing==13:
	    print("your screen1_ticket confirmed @ 6:50 PM")
	    
elif screen1_show_timing==14:
	    print("your screen1_ticket confirmed @ 7:00 PM")
	    
elif screen1_show_timing==15:
	    print("your screen1_ticket confirmed @ 10:00 PM")
	  
	  
	  
print("select your seat number:")
seat_number=("1.a1-a50-first row\n2.b1-b50-middle row\n3.c1-c50 corner seat\n4.d1-d50-last row")
print(seat_number)
seat_no=input("chose your seat num:")
if seat_no=="1":
	print(f"you confirmed first row {seat_no}")
	
elif seat_no=="2":
	print(f"you confirmed middle row {seat_no}")
	
elif seat_no=="3":
	print(f"you confirmed corner seat {seat_no}")
	
elif seat_no=="4":
	print("you confirmed last row {seat_no}")
	
else:
	print("sorry !")
	

confirm=int(input("press 1 to confirm:"))
if confirm==1:
	print("your ticket is confirmed")
	
	

x=datetime.datetime.now()
print(x)

	
