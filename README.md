# Python-Class-Work
# Q1define a function name sum_of_list.
#the parameter will find the sum of all the element in the list an return the summation
#SOLUTION
# defining the function
def sum_of_list():
    #naming the variable list
    List = [1,2,3,4,5]
    #finding the summation of the list's element
    sum_list = sum(List[ : ])
    #returning the sum
    
    print(sum_list)
    
 #calling out the function   
sum_of_list()



def two_level_sum():
    a_list = [[5,8], [1,4,7], [10], 3]
   
    sum_a_list1 = a_list[0] + a_list[1] +a_list[2]
    sum_a_list2 = sum(sum_a_list1, a_list[-1])
    print(sum_a_list2)
    
    
two_level_sum()
