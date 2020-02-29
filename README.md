# Dynamic-Programming
# 1. Fabonacci Series

    int fabonacci(int n)
    {
        int arr[n+2];
        arr[0]=0;
        arr[1]=1;
        for(int i=2;i<=n;i++)
            arr[i]=arr[i-1]+arr[i-2];

        return arr[n];
    }
