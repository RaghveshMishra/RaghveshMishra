print("select. Level")
print("Level1. Easy")
print("Level2. Medium")
print("Level3. Hard")
select=input("your choice")
if select == "Easy" or select == '1':
    print("q1:.Which technology company has launched a campaign named Make Small Strong")
    print("a. Microsoft")
    print("b.Google")
    print("c.Amazon")
    print("d.Facebook")
    q1=input("your choice: ")
    if q1=='B' or q1=='b':
        print("correct")
    else:
        print("incorrect \nans=google",)
    
    print("q2:Who has been appointed as the new Chairperson of Telecom Regulatory Authority of India (TRAI)")
    print("a. P. D. Vaghela")
    print("b. Sumanta Chaudhry")
    print("c. Shalabh Mathur")
    print("d. Ajay Vijayvergiya")
    q2=input("your choice: ")
    if q2=='A' or q2=='a':
        print("correct")
    else:
        print("incorrect \nans=P.D Vaghela")

    print("q3:What is the name of the initiative by Defence Ministry to identify innovations created by Indian Armed Forces personnel?")
    print("a. Idea Force")
    print("b. iDEX4Fauji")
    print("c. Mission Fauji")
    print("d. marris")
    q3=input("your choice: ")
    if q3=='C' or q3=='c':
        print("correct")
    else:
        print("incorrect \nans=Mission Fauji")

    print("q4:Which Union Ministry launched the ‘CSIR- Technologies for rural development’?")
    print("a. Ministry of Science and Technology")
    print("b. Ministry of Education")
    print("c. Ministry of Agriculture and Farmers Welfare")
    print("d. Ministry of Rural Development")
    q4=input("your choice: ")
    if q4=='A' or q4=='a':
        print("correct")
    else:
        print("incorrect \nans=Ministry of Science and Technology")

    print("q5:Which technology company has committed to pay USD 1 billion for next 3 years to the publishers for their content?")
    print("a.Facebook")
    print("b.Google")
    print("c.Amazon")
    print("d.Apple")
    q5=input("your choice: ")
    if q5=='B' or q5=='b':
       print("correct")
    else:
       print("incorrect \nans=google")
elif select == "medium" or select == '2':
    
    print("q6Which country is to send the world’s first mining robot named ‘Asteroid Mining robot’ into space?")
    print("a.India")
    print("b.United States")
    print("c.China")
    print("d.Israel")
    q6=input("your choice: ")
    if q6=='A' or q6=='a':
        print("correct")
    else:
        print("incorrect \nans=china")

    print("q7:Which organization has released a report on Crime against Scheduled Castes (SCs) and Scheduled Tribes?")
    print("a. CBI")
    print("b. NCRB")
    print("c. NCBC")
    print("d. National Administrative Tribunal")
    q7=input("your choice: ")
    if q7=='B' or q7=='b':
        print("correct")
    else:
        print("incorrect \nans=NCRB")
    print("q9:Ministry of Defence has designated Alpha Design Technologies Limited for upgrading which defence system?")
    print("a. Pinaka Artillery System")
    print("b. Pechora surface to air systems")
    print("c. Brahmos Missile System")
    print("d. Navic System")
    q9=input("your choice: ")
    if q9=='B' or q9=='b':
        print("correct")
    else:
        print("incorrect \nans=Pechora Artillery System")
    print("q10:The E Way Bill is implemented under the aegis of which body?")
    print("a. Central Board of Direct Taxes")
    print("b. Central Board of Indirect Taxes and Customs")
    print("d. Enforcement Directorate")
      
    q10=input("your choice: ")
    if q10=='B' or q10=='b':
         print("correct")
    else:
        print("incorrect \nans=Central Board of Indirect Taxes and Customs")
else:
    select == "Hard" or select == '3'
    print("q11.Which country is to send the world’s first mining robot named ‘Asteroid Mining robot’ into space?")
    print("a.India")
    print("b.United States")
    print("c.China")
    print("d.Israel")
    q11=input("your choice: ")
    if q11=='A' or q11=='a':
        print("correct")
    else:
        print("incorrect \nans=china")

    print("q12:Which organization has released a report on Crime against Scheduled Castes (SCs) and Scheduled Tribes?")
    print("a. CBI")
    print("b. NCRB")
    print("c. NCBC")
    print("d. National Administrative Tribunal")
    q12=input("your choice: ")
    if q12=='B' or q12=='b':
        print("correct")
    else:
        print("incorrect \nans=NCRB")
    print("q13:Ministry of Defence has designated Alpha Design Technologies Limited for upgrading which defence system?")
    print("a. Pinaka Artillery System")
    print("b. Pechora surface to air systems")
    print("c. Brahmos Missile System")
    print("d. Navic System")
    q13=input("your choice: ")
    if q13=='B' or q13=='b':
        print("correct")
    else:
        print("incorrect \nans=Pechora Artillery System")
    print("q14:The E Way Bill is implemented under the aegis of which body?")
    print("a. Central Board of Direct Taxes")
    print("b. Central Board of Indirect Taxes and Customs")
    print("d. Enforcement Directorate")
      
    q14=input("your choice: ")
    if q14=='B' or q14=='b':
         print("correct")
    else:
        print("incorrect \nans=Central Board of Indirect Taxes and Customs")
    question = {q11:"a",q12:"b",q13:"b",q14:"b"}
    score = 0
    for i in question:
        print(i)
        if ans==question[i]:
            print("correct")
            score = score+1
        else:
            print("incorrect \nans = a.microsoft")
    print("final score is:",score)
    

