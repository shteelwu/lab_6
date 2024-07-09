```c
#include <stdio.h>
#include <math.h>

int main() {
    int x1, y1, x2, y2;
    
  printf ("Enter x1, y1 and x2, y2:");
    scanf("%d %d %d %d", &x1, &y1, &x2, &y2);
    
 
    double length = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));
    
  
    printf("Result:%.6f\n", length);
    
    return 0;
}
