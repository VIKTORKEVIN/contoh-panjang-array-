# contoh-panjang-array-

    #include<stdio.h>

    void cetak_mundur (char S[])
    {
    int i,n;
    for(n=0;n<S[n];n++);
        printf("panjang array = %d\n",n);
    for(i=n-1;i>=0;i--)
    {
        printf("%C",S[i]);
    }
    }
    int main()
    {
    char str[50]= "anton";
    cetak_mundur (str);
    }
    
![img](https://raw.githubusercontent.com/VIKTORKEVIN/contoh-panjang-array-/master/contoh%20(panjang%20array).png)
