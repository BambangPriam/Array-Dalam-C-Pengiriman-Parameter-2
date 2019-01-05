# Array-Dalam-C-Pengiriman-Parameter-2

    #include<stdio.h>

    void tukar(int array[2]){
    int t=array[0];
    array[0]=array[1];
    array[1]=t;
    }

    void main(){
    int array[2] = {1,2};
    printf("before %d - %d\n", array[0], array[1]);
    tukar(array);
    printf("after %d -%d", array[0], array[1]);
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Array-Dalam-C-Pengiriman-Parameter-2/master/Pengiriman%20Parameter%202.png)
