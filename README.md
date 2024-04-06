# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
Developed by:Prashanth.K
Register number:212223230152

def binarySearchIter(array, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if array[mid]==k:
            return mid
        elif array[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
array = eval(input())
array.sort()
k = eval(input()) 
print(array)
res=binarySearchIter(array,k,0,len(array)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)

```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
Developed by:Prashanth.K
Register number:212223230152

def binarySearchIter(array, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if array[mid]==k:
            return mid
        elif array[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
array = eval(input())
array.sort()
k = eval(input()) 
print(array)
res=binarySearchIter(array,k,0,len(array)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)

```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
Developed by:Prashanth.K
Register number:212223230152

def binarySearchIter(array, k, low, high):
    while low<=high:
        mid=low+(high-low)//2
        if array[mid]==k:
            return mid
        elif array[mid]<k:
            low=mid+1
        else:
            high=mid-1
    return -1
array = eval(input())
array.sort()
k = eval(input()) 
print(array)
res=binarySearchIter(array,k,0,len(array)-1)
if res==-1:
    print("Element not found")
else:
    print("Element found at index: ",res)









```
## Output
(i) # Use a linear search method to match the item in a list.
![Screenshot 2024-04-06 083334](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/e72c682e-feee-4179-b760-42f851c10d6d)
![Screenshot 2024-04-06 083345](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/bfbe6f00-9dfa-40aa-a335-27195dec9477)


(ii) #Find the element in a list using Binary Search(Iterative Method).
![Screenshot 2024-04-06 083402](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/8ccf5f86-2b3d-4dbe-ab10-298f3e7ef914)
![Screenshot 2024-04-06 083418](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/4de4e53e-7e07-43f0-b63e-f59abb751d11)



(iii) # Find the element in a list using Binary Search (recursive Method).
![Screenshot 2024-04-06 083435](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/25387766-a0f8-48e4-920b-3f26c3dc7593)
![Screenshot 2024-04-06 083445](https://github.com/PRASHANTHRATHI/Search-Algorithms/assets/145743120/8bd9fd1e-c4e9-4207-a89a-6f5c79c99447)












## Result
Thus the linear search and binary search algorithm is implemented using python programming.
