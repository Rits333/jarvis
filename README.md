# jarvis
trying to make jarvis using python



import os
import pyttsx3
print("*************************************************************************************************************************************************************************************")
print("\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\tGOOD MORNING \t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t")
print("*************************************************************************************************************************************************************************************")
pyttsx3.speak("GOOD morning sir")
pyttsx3.speak("welcome to your pc ")
pyttsx3.speak("How may i help you")
print()
while True:
	pyttsx3.speak(" just type your requirment")
	print("Type your requirment: ",end=' ')
	p = input()
	
	if ("run" in p) and ("chrome" in p):
              	
		while True:
			
			print("Enter website you want to open")	
			pyttsx3.speak("enter the website which you want to start ")
			q = input()
			
			
			if("google" in q):
				pyttsx3.speak("opening  the  browser for you please wait ")
				os.system("chrome  google.com")
				break
				
			elif("facebook" in q):
				pyttsx3.speak("opening  the  browser for you please wait ")
				os.system("chrome  facebook.com")
				break
					
				
			elif("youtube" in q):
				pyttsx3.speak("opening  the  browser for you please wait ")
				os.system("chrome  youtube.com")
				break
				
			elif("gmail" in q):
				pyttsx3.speak("opening  the  browser for you please wait ")
				os.system("chrome  gmail.com")
				break

			elif ("exit" in q) or (("quit" in q) or ("terminate" in q)):
				pyttsx3.speak("exiting from chrome")
				break		
				
			elif("help" in q):
				pyttsx3.speak("opening the help menu for you ")
				print("to run google type :-google")
				print("to run facebook type:-facebook")
				print("to run youtube type :-you tube")
				print("to run youtube type :-gmail")
				print("To exit type:- exit")
				
				
			else:
				print("dont support")
				print("or\n-type:- help")
				pyttsx3.speak("Make sure you typed right command or you can go to help menu ")
					
		
	elif(("run" in p) or  ("execute" in p )) and  (("notepad" in p) or ("editor" in p)) :
		pyttsx3.speak("please wait while opening notepad for you")
		os.system(" notepad ")	
	
	elif("run" in p)   and ("firefox" in p) :
		pyttsx3.speak("please wait while opening firefox for you")
		os.system(" firefox ")	
	
	elif ("run" in p) and(("acrobat" in p)or ("pdf" in p)):
		pyttsx3.speak("opening pdf viewer ")
		os.system("Acrobat")
	
	
	elif ("run" in p) and(("player" in p)or ("media" in p)):
		pyttsx3.speak("opening media player ")
		os.system("wmplayer")

	
 	
	
	elif ("run" in p) and ("office" in p):
              	
		while True:
			
			print("Enter which office software you want to use")	
			pyttsx3.speak("Enter which office software you want to use ")
			r = input()
			
			
			if("word" in r):
				pyttsx3.speak("opening  the  word ")
				os.system("start WINWORD")
				break
				
			elif("excel" in r):
				pyttsx3.speak("opening  the  excel ")
				os.system("start EXCEL")
				break
					
				
			elif("powerpoint" in r):
				pyttsx3.speak("opening  the  powerpoint ")
				os.system("start POWERPNT")
				break
				
			elif("outlook" in r):
				pyttsx3.speak("opening  the  outlook ")
				os.system("start OUTLOOK")
				break

				
			elif ("exit" in r) or (("quit" in r) or ("terminate" in r)):
				pyttsx3.speak("exiting from office ")
				break
						
				
			elif("help" in r):
				pyttsx3.speak("opening the help menu for you ")
				print("to open word type:-word")
				print("to open excel type:-excel")
				print("to open powerpoint type :-powerpoint")
				print("to open outlook type :-outlook")
				print("To exit type:- exit")
				
			else:
				print("dont support")
				print("or\n-type:- help")
				pyttsx3.speak("Make sure you typed right command or you can go to help menu ")






	


	




	elif ("help" in p):
		pyttsx3.speak("opening the help menu for you ")
		print("to run chrome type :-\t\trun chrome")
		print("to run notepad type:-\t\trun notepad")
		print("to run media player type :-\trun media")
		print("to run firefox type :-\t\t run firefox")
		print("to run pdf viewer type :-\trun pdf/acrobat")
		print("to run office :-\t\trun office")
		print("To exit from program :-\t\texit")
		
		
		

	elif ("exit" in p) or (("quit" in p) or ("terminate" in p)):
		pyttsx3.speak("closing the program sir thank you  Have a nice day ahead")
		break
	
	

	else:  
		print("dont support")
		print("or\n-type:- help")
		pyttsx3.speak("Make sure you typed right command or you can go to help menu ")
