# game_python
Python game to find out the date of birth
list1=[[1,3,5,7],[9,11,13,15],[17,19,21,23],[25,27,29,31]]
list2=[[2,3,6,7],[10,11,14,15],[18,19,22,23],[26,27,30,31]]
list3=[[4,5,6,7],[12,13,14,15],[20,21,22,23],[28,29,30,31]]
list4=[[8,9,10,11],[12,13,14,15],[24,25,26,27],[28,29,30,31]]
list5=[[16,17,18,19],[20,21,22,23],[24,25,26,27],[28,29,30,31]]


def display(current_matrix):
    for i in range(0,len(current_matrix)):
        print(current_matrix[i])

date=0
display(list1)
inp = input("Enter yes if birthday is present, else no")
if inp == 'yes':
    date +=  list1[0][0]

display(list2)
inp = input("Enter yes if birthday is present, else no")
if inp == 'yes':
    date +=  list2[0][0]

display(list3)
inp = input("Enter yes if birthday is present, else no")
if inp == 'yes':
    date +=  list3[0][0]

display(list4)
inp = input("Enter yes if birthday is present, else no")
if inp == 'yes':
    date +=  list4[0][0]

display(list5)
inp = input("Enter yes if birthday is present, else no")
if inp == 'yes':
    date +=  list5[0][0]
print(date)
