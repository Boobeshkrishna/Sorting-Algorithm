# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: your name BOOBESH PM
RegisterNumber: 212222233001
''
def selection_sort(nums):
    for i in range(len(nums)):
        lowest_value=i
        for j in range(i+1,len(nums)):
            if nums[j]<nums[lowest_value]:
                lowest_value=j
        nums[i],nums[lowest_value]=nums[lowest_value],nums[i]
    
    
    
    
list_of_nums = eval(input())
selection_sort(list_of_nums)
print(list_of_nums)
# use the selection sort function
# print the sorted list
```
ii)	#Insertion Sort
```
''' 
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: your name
RegisterNumber: 
'''
def insertion_sort(nums):
    for i in range(1,len(nums)):
        item_to_insert=nums[i]
        j=i-1
        while j>=0 and nums[j]>item_to_insert:
            nums[j+1]=nums[j]
            j-=1
        nums[j+1]=item_to_insert
        
list_of_nums=eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)
    
    
# use the insertion sort function to get the sorted list
# print the sorted list
```

## Output:
![image](https://github.com/Boobeshkrishna/Sorting-Algorithm/assets/141472052/527f4cf9-9597-4578-a11e-cafeb7483f76)
![image](https://github.com/Boobeshkrishna/Sorting-Algorithm/assets/141472052/7e2d4d4d-ed1c-406b-8827-df0b1c77a0a0)
![4 a1](https://github.com/Boobeshkrishna/Sorting-Algorithm/assets/141472052/9cca51d4-1e0a-4f01-8a3d-7824739b27e3)
![4a2](https://github.com/Boobeshkrishna/Sorting-Algorithm/assets/141472052/8c39316f-ad19-43bc-85b3-fb85cb6b5630)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
