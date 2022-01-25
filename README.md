# code
#include&lt;stdio.h> #include&lt;stdlib.h> #define size 10 int binsearch(int[], int, int, int); int main() {  int num, i, key, position;  int low, high, list[size];  printf("\nEnter the total number of elements");  scanf("%d", &amp;num);  printf("\nEnter the elements of list :");  for (i = 0; i &lt; num; i++) {  scanf("%d", &amp;list[i]);  }
