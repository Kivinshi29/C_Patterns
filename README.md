// Star Triangle Pattern

#include <stdio.h>

int main() {
    int i, j;
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

// Reverse Star Pattern

#include <stdio.h>

int main() {
    int i, j;
    for(i = 5; i >= 1; i--) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

// Number Pattern

#include <stdio.h>

int main() {
    int i, j;
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= i; j++) {
            printf("%d", j);
        }
        printf("\n");
    }
    return 0;
}

// Same Number Pattern

#include <stdio.h>

int main() {
    int i, j;
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= i; j++) {
            printf("%d", i);
        }
        printf("\n");
    }
    return 0;
}


// Pyramid Star Pattern

#include <stdio.h>

int main() {
    int i, j, space;
    for(i = 1; i <= 5; i++) {
        for(space = 1; space <= 5 - i; space++) {
            printf(" ");
        }
        for(j = 1; j <= (2*i - 1); j++) {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}



