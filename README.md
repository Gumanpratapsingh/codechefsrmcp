# codechefsrmcp

**Answer for Q.1**
#include <stdio.h>
int main()
{
int number, LD;
printf(" Enter a number"4589); -----> **_Here we are putting number outside the "" quotes which will produce error!_**
scanf("%d", &number);
LD = number / 10;
printf(" \n The Last Digit of a Given Number %d = %d", number, LD);
return 0;
}

**Answer 2**
int sumcal(int len, int* arr, int value)
{
int sum = 0;
for(int i =0 ; i< len-1; i++ )
{
if(arr[i]%value == 0)
sum =+ arr[i];
}
return sum;
} ---> **No error**



**Answer 4**
#include <stdio.h>
void main() {
char a='A';
a>10?printf("Yes");:printf("No");
return 0;
}
--->**It will produce error at ternary condition because we have to give condtion as "_conditon?statement_if_true:statement_if_false"_ 
and we are giving ; more in that place in line no.33 **

**Answer 5**
#include <iostream>
using namespace std;
int main() {
int o; i; s;  
for(o=5; o>=1; o--)
{
for(s=1 s<=5-o s++)
cout<<" ";
for (i=1 i<=o i++){
cout>>"*";}
cout<<endl;
}}}
**At line 43**  ----> **here we are giving ; after every variable we should give , 
  **at line 46** ---> we are not giving ; after every condition in for loop
  same for line 48
  line 49 operator used for cout is wrong. we should use << as  used in line 50
  
  
**Answer 6**
  z=int(“Enter a number:”)
for in range [0,9]:
if z=x:
print(“They are equal”);
else:
print(“They are not equal”)
  here we are not giving ; after line end in the line 64
  
  
  
**Answer 7**
#include <iostream>
class test{
int my_variable;
}
int main() {
test code_chef;
cin>>code_chef.my_variable;
if(code_chef.my_variable%2==0){
cout<<"Even";
}
else{
cout<<odd;
}
return 0;
}
  
--> we are not giving the ; used for stating the end of class statement at the line 73
  and as we are not declaring the access modifier of the class data function,it defaults will be private and we are accessing it from the main finction it gives error line 72
  

  
 **Answer 8**
  #include<iostream>
using namespace std
void printSums(int N)
{
int start=1, end=(N+1)/2;
while (start<end)
{
int sum=0;
for (int i=start;i<=end;i++)
{
sum=+i;
if (sum == N)
{
for (j=start,j<=I,j++)
cout<<j<<" ";
cout<<"/n";
break;
}
if (sum>N)
break
}
sum=0;
start++;
}
}
int main()
{
int n;
cin>>n;
printsums(n);
return 0;
}
  
--> didnt close the namespace std, we will use ; to close the line
  j and I at line 105 was not declared, closing ; was not used in the for loop in the same line
  line 111 closing ; after break
  printSums was the fumction we declare but we are calling the printsums both are diff as c++ is case sensitive we should call PrintSums
  
  
  **Answer 9**
  #include <iostream>
using namespace std;
int main() {
int length
cout<<enter the length of the array"<<endl;
cin>>length;
int array(length];
for(int i=0;i<length;i++){
cin>>array[i];
}
int min=array[0];max=array[0];
for(int i=1;i<length;i++){
if(array[i]>max)
max = array[i];
else if(array[i]<<min)
min = array[i];
}
cout<< min<<" "<<max;
return std;
}
  --->
  **at line 135 same length was not closed using the ; 
  **At line 136 we are using "" to show the statement enter the lenght the length of array we used the ending quote but we are not using the intializing quote
  in the array length statement we are using ( bracket insted of [ at line 138
  in the line 142 we used ; instead of the , that breaks the intialization of the max variable 
  and at last we are retiurning the std at the line 150
  
  
  **Answer 10*
  #include <stdio.h>
*include <string.h>
main()
{
int t,i,diff_count;
scanf("%d";&t)
char s[100001],
while(t+-){
diff_count=0;
scanf("%s",s);
for(int i=0;i<strlen(s)-1;i++){
if(s[i]===s[i+1])

diff_count++;
}
printf("%d\n",diff_count);
return 0;
}
       --->in the line 162 we use * instead of hash #
  in the main function we forgot to use the int in the line 163
  using the ; instead of the comma , and not using the line end ; in the scanf in the line 166
  same in the char line 167 we are not ising the ; in the end of line
  in the line 168 we are t+- which is wrong either we should use t-- or t++
  in the line 172 we are uding 3 three = operator it should be == two which will check the equal to thing
  
  
  **Answer 3**
  #include <stdio.h>
int main()
{
for(int i=1;i <= 4;i--)
{
for(int j=1;j <= 4; j++)
{
if(i != j)
{
printf("*");
}
else
{
printf(" ");
}
}
printf("\n");
}
return 0;
}
---> no error acc to me
  
