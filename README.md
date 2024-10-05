#include<stdio.h>
int main(){
    int n,i,max;
    int arr[n];
    printf("enter the no. of elements");
    scanf("%d",&n);
    printf("enter the elements");
    for(i=0;i<n;i++){
        scanf("%d",&arr);

    }
    max=arr[0];
    for(i=0;i<n;i++){
        if(arr[i]>max){
        max=arr[i];

        }
    }
    printf("maximum no. in array is %d",max);

return 0;
}
