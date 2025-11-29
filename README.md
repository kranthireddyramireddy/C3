# C3
swap numbers
#include<stdio.h>
#include<stdlib.h>
int main(){
    int *p = malloc(3 * sizeof(int));
    printf("malloc :%d %d %d", p[0], p[1], p[2]);
    free(p);
    return 0;
}
