# Heap Sort using Min Heap

Given an array of elements, sort the array in decreasing order using min heap.

Algorithm :

1. Build a min heap from the input data.
2. At this point, the smallest item is stored at the root of the heap. Replace it with the last item of the heap followed by reducing the size of heap by 1. Finally, heapify the root of tree.
3. Repeat above steps while size of heap is greater than 1.

Note :Heap Sort using min heap sorts in descending order where as max heap sorts in ascending order


Time complexity:

It takes O(logn) for heapify and O(n) for constructing a heap. 
Hence, the overall time complexity of heap sort using min heap or max heap is O(nlogn)


Given an array of elements, sort the array in decreasing order using min heap.

Examples:

Input : arr[] = {5, 3, 10, 1}

Output : arr[] = {10, 5, 3, 1}
