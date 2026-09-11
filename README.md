#include <stdio.h>

int main()
{
    float R1, R2, V, RN, IN;

    printf("Enter voltage source V: ");
    scanf("%f", &V);

    printf("Enter R1: ");
    scanf("%f", &R1);

    printf("Enter R2: ");
    scanf("%f", &R2);

    // Norton resistance
    RN = (R1 * R2) / (R1 + R2);

    // Norton current
    IN = V / R1;

    printf("\nNorton Resistance (RN) = %.2f Ohms", RN);
    printf("\nNorton Current (IN) = %.2f A\n", IN);

    return 0;
}

Example: If "V = 12 V", "R1 = 4 Ω", and "R2 = 6 Ω":

Norton Resistance (RN) = 2.40 Ohms
Norton Current (IN) = 3.00 A

Formula:

- "RN = R1 × R2 / (R1 + R2)"
- "IN = V / R1"

This assumes a simple circuit with a voltage source and two resistors.# Norton-s.p
Norton ' s c programing code..⚡
