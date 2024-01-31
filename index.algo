function insertionSort(arr) {
    // Start from the second element, as the first is considered sorted
    for (let i = 1; i < arr.length; i++) {
        let key = arr[i];  // Pick the current element
        let j = i - 1;  // Index of the last element in the sorted sequence

        // Move elements greater than key to one position ahead of their current position
        while (j >= 0 && key < arr[j]) {
            arr[j + 1] = arr[j];
            j--;
        }

        // Insert the current element into the correct position in the sorted sequence
        arr[j + 1] = key;
    }
}

// Example usage:
let unsortedArray = [12, 11, 13, 5, 6];
insertionSort(unsortedArray);
console.log("Sorted array:", unsortedArray);