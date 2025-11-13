```pseudo
procedure LinearSearch(A, n, x){
    // Assumption: Array A has capacity n + 1
    A[n + 1] = x
    i = 1
    while(A[i] != x){
        i = i + 1
    }
    if(i == n + 1){
        return Not Found
    } else {
        return i
    }
}

```