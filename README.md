//# CAR-GAME
//GAME WITH OUT GRAPHICS
#include<stdio.h>
int game();
int main()
{
	int a;
	printf("\npress any number to start the car\n");
	scanf("%d",&a);
	int z;
	printf("\npress '101' for 'INSTRUCTIONS' \n");
	scanf("%d",&z);
	switch(z==101)
	{
		case 1:
			printf("\n1.IMAGINE MAP IN YOUR MIND\n");
			printf("\n2.THIS IS BASED ON YOUR IMAGINATION\n");
			printf("\n3.SO PLEASE PLAY FOR ENJOYMENT\n");
			printf("\n4.PLAY CAREFULLY\n");
			printf("\n FOR DIRECTIONS\n");
			printf("\n1.TAKE LEFT\n2.TAKE RIGHT\n3.TAKE REVERSE\n4.STOP\n5.HORN\n");
			break;
		case 0:
			printf("YOUR OUT OF THE GAME  MR.BLIND");
			exit(0);
			break;
	}
	int j;
for(j=0;j<10000000;j++)
{
	printf("%d",j);
	j=game();
}
}
int game()
{
	int i;
	scanf("%d",&i);
	switch(i)
	{
		case 1:
			printf("\nTAKEN LEFT \n");
			break;
		case 2:
			printf("\nTAKEN RIGHT \n");
			break;
		case 3:
			printf("\nTAKEN REVERSE \n");
			break;
		case 4:
			printf("\nSTOPPED \n");
			break;
		case 5:
			printf("\a \a \a \a");
			break;
		default:
			printf("\nenter the correct number stupid \n");
			printf("\n your out of the game\n");
			exit(0);
			break;
	}
}
