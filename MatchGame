#include <stdio.h>
#include <time.h>
#include <stdlib.h> 

int main(int argc, char** argv) {
	srand((unsigned)time(NULL));
	int Your,Computer,total,cget,youget,d;
	printf("\n请输入是计算机先拿火柴还是你先拿火柴（计算机为1，您为0）：");
	scanf("%d",&d);
	do{
	printf("\n请设置火柴的总数（总数不能小于0):");
	scanf("%d",&total); 
	}while(total<0);
	while(1){
		if(d==0){
			do{
				printf("\n目前剩余火柴为 %d 请输入你要拿的数目(你只能拿一根或者两根):",total);
				scanf("%d",&youget);
			}while(youget<1 || youget>2);
			total-=youget;
			if(total<=0){
				printf("\n你赢了!!!");
				break;
			}
			if(total%3==0){
				if(rand()%2==1){
					total-=1;
				    printf("\n计算机拿了一根火柴");
				}else{
					total-=2;
					printf("\n计算机拿了两根火柴");
				}
			}else{
				int k;
				k=total%3;
				total=total-(total%3);
				printf("\n计算机拿了 %d 根火柴",k);
			}
			if(total<=0){
				printf("\n计算机赢了!!!");
				break;
			}
		}else{
			if(total%3==0){
				if(rand()%2==1){
					total-=1;
				    printf("\n计算机拿了一根火柴");
				}else{
					total-=2;
					printf("\n计算机拿了两根火柴");
				}
			}else{
				int k;
				k=total%3;
				total=total-(total%3);
				printf("\n计算机拿了 %d 根火柴",k);
			}
			if(total<=0){
				printf("\n计算机赢了!!!");
				break;
			}
			do{
				printf("\n目前剩余火柴为 %d 请输入你要拿的数目(你只能拿一根或者两根):",total);
				scanf("%d",&youget);
			}while(youget<1 || youget>2);
			total-=youget;
			if(total<=0){
				printf("\n你赢了!!!");
				break;
			}
			}
			
		}
	printf("\n游戏结束\n");
	system("pause"); 
	return 0;
		 
	}

