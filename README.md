# baitap
#include<stdio.h>
#include<stdio.h>
int main(){
	int mang[100];
	int n;
	printf("Nhap vao n=");
	scanf("%d",&n);
	for(int i=0;i<n;i++){
		printf("mang[%d]=",i);
		scanf("%d",&mang[i]);
	}
	// in mang
		for(int i=0;i<n;i++){
			printf("mang[%d]=%d",i,mang[i]);
		}
	// tinh tong giai thua cua cac phan tu co trong mang
	    int S=0;
      int i;
	    for(i=1;i<=n;i++)
		{
	    	S=S*i;
		}
		printf("\nTong giai thua la: %d\n",S);
	//	
}
