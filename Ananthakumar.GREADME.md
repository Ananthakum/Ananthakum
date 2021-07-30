Code :
# Python program to print all 
# prime number in an interval
# number should be greater than 1
start = 11
end = 25
  
for i in range(start, end+1):
  if i>1:
    for j in range(2,i):
        if(i % j==0):
            break
    
<!---
Ananthakum/Ananthakum is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
