#include<stdio.h>
#include<stdlib.h>
int main()		
{
	FILE *f1;
	int i=0,n;
	struct emp
     {
	char ename[20];
	int age,sal;
      }e1[100];
      f1=fopen("emp.txt","r");
	if(f1==NULL)
	{
		printf("File not found");
		exit(0);
	}
	while(!feof(f1)) 
	{
	fscanf(f1,"%s%d%d",&e1[i].ename,&e1[i].age,&e1[i].sal);
	n=i;
		for(i=0;i<n;i++)
	{	
	printf("\n Emp name=%s",e1[i].ename);
	printf("\n Emp Age=%d",e1[i].age);
	printf("\n Emp name=%d",e1[i].sal);
	}
		fclose(f1);
}
}
