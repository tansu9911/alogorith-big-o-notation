#include <iostream>
using namespace std;

void insertionSort(int A[], int n) {
    for (int i = 1; i < n; i++) {       // Runs n-1 times → O(n)
        int key = A[i];                  // O(1)
        int j = i - 1;

        // Move elements greater than key
        while (j >= 0 && A[j] > key) {   // Worst case: O(n) comparisons per i
            A[j + 1] = A[j];             // O(1)
            j--;
        }
        A[j + 1] = key;                  // O(1)
    }
}

int main() {
    int n;
    cout << "Enter number of elements: ";
    cin >> n;

    int A[n];
    cout << "Enter elements:\n";
    for (int i = 0; i < n; i++) cin >> A[i];  // O(n)

    insertionSort(A, n);                        // O(n^2) worst case

    cout << "Sorted array: ";
    for (int i = 0; i < n; i++) cout << A[i] << " "; // O(n)
    cout << endl;

    return 0;
}
