- 👋 Hi, I’m @Amritha2705
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Amritha2705/Amritha2705 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
int main()
{
int i,fact=1,number;
printf("Enter a number:");
scanf("%d",number);
for(i=1;i<=number;i++)
{
fact=fact*i;
}
printf("Factorial of %d is :%d",number,fact);
return 0;
}
