#include <stdio.h>

int main() {
    float base_cost = 40.0; // Base cost of call taxi
    
    // Input of needable data 
    float demand, distance, duration;
    printf("Enter demand level, distance and duration: \n");
    scanf("%f", &demand);
    scanf("%f", &distance);
    scanf("%f", &duration);
    
    float commision = 0.29 * (demand * 0.4); // Calculating commision
    float demand_mult = demand / 100.0 + 1.0; // Making demand multiplier for balancing cost
    
    float final_cost = ((base_cost * demand_mult) + (distance * 3) + (duration * 2)) * (commision*0.5); // Formula of trip cost
    printf("This trip will cost you %.2f rub.", final_cost);
    
    return 0;
}
