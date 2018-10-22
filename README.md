# assighment
by Asad ullah (09)
#include<stdio.h>
int main()
{
	int count[7]={10,11,12,13,14,15,16};
	int ans[7];
	int add,all=0;
	float avg;
	for (add=0;add<8;add++)
	{
		all=all+count[add];
	}
	avg=all/7;
	
	printf("the sium of all is %d",all);
	printf("\nAvrage is%f",avg);
	for(add=0;add<=6;add++)
	{
		ans[6]=(count[add]-avg)*(count[add]-avg);
		printf("\n%d",ans[6]);
	}
	 return 0;
}
