name=input("Enter your name:")
clas=int(input("Enter your class:"))
height=int(input("Enter your height:"))
weight=int(input("Enter your weight:"))

agility=input("Enter your agiility in terms Low/Med/High")
speed=input("Enter your speed in terms Low/Med/High")
strength=input("Enter your strength in terms Low/Med/High")
details={"sname":"name","sclass":clas,"sheight":height,"sweight":weight,"ssport":"sport","sagility":"agility","sspeed":"speed","sstrength":"strength"}

def givesport():
 agility=details['sagility']
 speed=details['sspeed']
 strength=details['sstrength']
 if (agility=="High" and strength=="Med" and speed=="High"):
  details[name][sport]="Cricket"
  if (agility=="High" and strength=="Med" and speed=="High"):
   details[name][sport]="Chess"
  elif (agility=="High" and strength=="High" and speed=="High"):
   details[name][sport]="Football"
 print(details)

           
givesport()


