print(''' 
  from all the mensioned zodiac signs
 1)aries
 2)tauras
 3)gemini
 4)cancer
 5)leo
 6)virgo
 7)libra
 8)scorpio
 9)segitteriouys
 10)capricorn
 11)aquarious
 12)pisces
 ''' )
s=int(input("pick your sign no and press enter\n"))
print(s)
 
if s==1:
   print("Today will be somehow good. Money which was stuck will be recovered now, it will increase liquidity in the business. There will be some good news in terms of job, your performance will be good, and you will expect promotions. There will be some good news in terms of legal matters also")
elif s==2:
   print("Today will be somehow good. Money which was stuck will be recovered now, it will increase liquidity in the business. There will be some good news in terms of job, your performance will be good, and you will expect promotions. There will be some good news in terms of legal matters also")
elif s==3:
   print("Spouse will approve of your idea regarding an issue without much convincing. A loan applied for may take its own time in materialising, but will be released in good time. Your firm resolution to remain totally fit may find you burning the track! Don’t remind senior about a job that remains incomplete as you may have to burn the midnight oil! You will take a step nearer to resolving a property dispute. There is no point in getting oversensitive about issues that have no long-term effects. Travelling to a distant place with lover becomes a blessed journey of togetherness") 
elif s==4:
   print("Financial worries become a thing of the past, as money comes to you from an unexpected source. Health of a family member may cause a bit of a concern, but will be nothing serious. Remain regular in your workouts, if you are serious of coming back in shape. Those heading for a vacation are poised to enjoy every moment of it! Possession of a house or apartment is likely to be offered soon. Someone may influence you to change your outlook in life and it will be for your own good. Celebrations regarding a promotion or a raise are just round the corner for some.")  
elif s==5:
   print("Sticking to routine will find you fit and energetic on the health front. Improvements in ancestral house are likely to be carried out. Your networking capabilities will smoothen the process of getting something officially done. You are likely to find your financial circumstances improving, as money begins to flow in. Focus of a family youngster may waver, if you don’t give the right direction to him or her. You will be beside yourself with happiness as a most pleasant surprise comes your way. You may opt for going Dutch with friends, if you don’t want any extra financial burden on your head.")  
elif s==6:
   print("virgo")  
elif s==7:
   print("libra")  
elif s==8:
   print("scorpio")  
elif s==9:
   print("seggiterrous") 
elif s==10:
   print("capricorn") 
elif s==11:
   print("aquarious") 
elif s==12:
    print("pisces") 
else:
    print("hey sure about the no")
next =True if  input("/nshall we do it again?(Y/N)")=="Y"  else False


