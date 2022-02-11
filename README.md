# 11-2-22-assignment2
sno=int(input('enter sno:'))
sname=input('enter sname:')
sgroup=input('enter sgroup:')
s1=int(input('enter Maths marks:'))
s2=int(input('enter Physics marks:'))
s3=int(input('enter Computers marks:'))
s4=int(input('enter Telugu marks:'))
s5=int(input('enter English marks:'))
s6=int(input('enter ICT marks:'))
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>=91:
    print('O-Grade')
elif avg>=81:
    print('A-Grade')
elif avg>=71:
    print('B-Grade')
elif avg>=60:
    print('C-Grade')    
elif avg>=50:
    print('D-Grade')
elif avg>=40:
    print('PASS')
else:
    print('FAIL')


OUT PUT
enter sno:1
enter sname:satya
enter sgroup:mpcs
enter Maths marks:85
enter Physics marks:80
enter Computers marks:76
enter Telugu marks:80
enter English marks:87
enter ICT marks:79
A-Grade
