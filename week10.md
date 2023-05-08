# 알고리즘 10주차

```
1부터 100까지 더하기
```

```
#include <stdio.h>

int main(void)
{
    int i, n, sum;
    
    i = 1;
    sum =0;
    
    while (i < 101) {
        printf("정수를 입력하시오: ");
        scanf("%d", &n);
        sum = sum + n;
        i++;
        
    }
    
    printf("합계는 %d입니다.\n");
    
    return 0;
}
```
<hr>

```
do-while문 이용해서 구구단 2단 출력하기
```

```
#include <stdio.h>

void main() {
	int dan = 2; //단

	do {
		int count = 1;

		printf(" --%d단--\n", dan);
		do {
			printf("%d X %d = %d\n",dan,count,dan*count);
			count++;
		} while (count <= 9);

		printf("\n\n");

		dan++;
	} while (dan <= 2);
}
```
<hr>

```
for문 이용해서 1-100까지 더하기
```

```
#include <stdio.h>

int main(void)
{
    int sum = 0;
    int count = 0;
    
    for (count=1; count<=100; count++)
    {
        sum = sum + count;
    }
    
    printf("%d", sum);
    
    return 0;
}
```
ㄴ 답 : 5050
<hr>

