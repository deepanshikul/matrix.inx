# matrix.inx
Developed by deepanshi
<stdio.h> int main() { int test[1][4][7];

printf("Enter 10 values: \n");

for (int i = 0; i < 1; ++i) { for (int j = 0; j < 4; ++j) { for (int k = 0; k < 7; ++k) { scanf("%d", &test[i][j][k]); } } }

// Printing values with proper index.

printf("\nDisplaying values:\n"); for (int i = 0; i < 1; ++i) { for (int j = 0; j < 4; ++j) { for (int k = 0; k < 7; ++k) { printf("test[%d][%d][%d] = %d\n", i, j, k, test[i][j][k]); } } }

return 0; }
