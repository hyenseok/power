#include <stdio.h>
//1부터 5까지의 자연수가 각각 적힌 5장의 카드 중에서
//동시에 두 장을 뽑아 만들 수 있는 두 자리의
//자연수를 모두 구하시오.//

int main()
{
	int a , b;

	for (a = 1; a <= 5; a++)
	{	
		
			for (b= 1 ; b <= 5; b++)
			{
				if (a != b) {


					printf("%d%d\n", a, b);
				}
			}

		}
	return 0;
	
	}
