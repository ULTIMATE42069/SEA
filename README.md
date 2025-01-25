# include <stdio.h> 
int main () 
{ 
    float grade; 
    printf ("Enter your grade (0 to 10)\n"); 
    scanf ("%f", &grade); 
    if (grade == 10) 
        printf ("Grade:O, Performance: Outstanding"); 
    else if (grade >= 9) 
        printf ("Grade:A+, Performance: Excellent"); 
    else if (grade >= 8) 
        printf ("Grade:A, Performance: Very Good"); 
    else if (grade >= 7) 
        printf ("Grade:B+, Performance: Good"); 
    else if (grade >= 6) 
        printf ("Grade:B, Performance: Above Average"); 
    else if (grade >= 5.5) 
        printf ("Grade:C+, Performance: Average"); 
    else if (grade >= 5) 
        printf ("Grade:C, Performance: Satisfactory"); 
    else  
        printf ("Grade:F, Performance: Fail"); 
} 
