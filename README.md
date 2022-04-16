# Count-Vowel-in-String
# find Vowel a=input("Enter the string")
string=a.lower()

print(string)

count=0

list=["a","e","i","o","u"]


for char in string:

    if char in list:
        
        count=count+1

print("number given the sentence",count)  


