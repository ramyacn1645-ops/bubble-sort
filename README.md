# bubble-sort
#iclude<stdio.h>
int main(){
    int n,i,j,temp;
    printf("enter the number of students in a class:\n);
    scanf("%d",&n);
    int score[n];
    for(i=0;i<n;i++){
        printf("enter scores:\n);
        scanf("%d",&score[i]);
    }
    for(i=0;i<n-1;i++){
        for(j=0;j<n-i-1;j++){
            if(score[j]<score[j=1]{
            temp=score[j];
            score[j]=score[j+1];
            score[j+1]=score[j];
            }
        }
    }
    for(i=0;i<n;i++){
        printf("%fd",score[i]);
    }
return 0;
}
