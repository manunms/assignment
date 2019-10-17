# assignment
AngularJS assignment

Problem Statement- Create a sort template in Angular JS, demonstrate implementation of Quick, Heap and Merge Sort.

Logic- User inputs values in array which is dynamically sorted on button click. The code for input and sorting is stored in a controller and accessed by ng-controller directive. The elements in array are displayed using ng-repeat directive. 

Merge sort, Quick sort and Heap sort are all examples of sorting algorithms. 
1. Merge Sort - It is a Divide and Conquer algorithm. The algorithm divides the array in two halves, recursively sorts them and finally merges the two sorted halves. Its best case complexity is O(n log n).

2. Quick sort - It is a Divide and Conquer algorithm. The algorithm picks a pivot element, rearranges the array elements in such a way that all elements smaller than the picked pivot element move to left side of pivot, and all greater elements move to right side. Finally, the algorithm recursively sorts the subarrays on left and right of pivot element. Its best case complexity is O(n log n). It is the fastest algorithm when the standard deviation of data is large.

3. Heap sort - The algorithm builds a heap tree from the input data. The largest item is stored at the root of the heap. It is replaced with the last item of the heap followed by reducing the size of heap by 1 and heap tree is created again. The steps repeat while size of heap is greater than 1. Its best case complexity is O(n log n).
