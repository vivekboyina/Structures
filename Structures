#include<stdio.h>
struct cars
{
	char company[100];
	char type[50];
	int tankcap;
	int numseats;
	int mileage;
};
int main()
{
	int n;
	printf("Enter number of cars\n");
	scanf("%d", &n);
	struct cars car[n];
	for(int i = 0; i < n; i++)
	{
		printf("Enter car%d's company\n", i+1);
		scanf(" %[^\n]s", car[i].company);
		printf("Enter car%d's type\n", i+1);
		scanf(" %[^\n]s", car[i].type);
		printf("Enter car%d's tank capacity\n", i+1);
		scanf(" %d", &car[i].tankcap);
		printf("Enter car%d's number of seats\n", i+1);
		scanf(" %d", &car[i].numseats);
		printf("Enter car%d's mileage\n", i+1);
		scanf(" %d", &car[i].mileage);
	}
	printf("-------------------------------------------------------------------------------------------------------------------------------------------\n");
	printf("| %-20s | %-20s | %-20s | %-20s | %-20s | %-20s |\n", "Serial no.","Car Company","Car Type","Fuel Tank Capacity","Number of seats","Mileage of car");
	printf("-------------------------------------------------------------------------------------------------------------------------------------------\n");
	for(int i = 0; i < n; i++)
	{
		printf("| %-20d | %-20s | %-20s | %-20d | %-20d | %-20d |\n",i+1,car[i].company,car[i].type,car[i].tankcap,car[i].numseats,car[i].mileage);
		printf("-------------------------------------------------------------------------------------------------------------------------------------------\n");
	}
}
