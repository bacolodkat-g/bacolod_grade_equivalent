#include <stdio.h>
int main (){
    // declare variabless
    float fahrenheit;
    float celsius;

     //input: fahrenheit
    printf("Write the fahrenheit value: "); //display: ask the user for an input
    scanf("%f", &fahrenheit);
    printf("Fahrenheit = %.2f", fahrenheit);

    //
    celsius = (fahrenheit - 32) * 5 / 9;
    //output: Fahrenheit
    printf("Celsius = %.2f", celsius);

    return 0;
}
