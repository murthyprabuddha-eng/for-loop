# for-loop
bag=["ball","pen","book"]
for things in bag:
    print(things)
  op:ball
     pen
     book

#to print a letter multiple time
name="spider"
for letter in name:
    print(letter*2)
op: ss
    pp
    ii
    dd
    ee
    rr

*********
string = "prabuddha"  # define the string

for index, char in enumerate(string, start=1):  # loop through string with index starting from 1
    print(char * index)  # repeat the character 'index' times and print it

----------------------------------------------------------------------------------------------------------

M = [12, 25, 29, 77, 874]  # list of numbers

for index, num in enumerate(M):  # loop through list getting index and value
    print(f"{num} is in {index}th index")  # print number with its index position
    op:12 is in 0th index
25 is in 1th index
29 is in 2th index
77 is in 3th index
874 is in 4th index


