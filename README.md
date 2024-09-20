### Weight Optimization and Performance Contribution for Hydrogen-powered Electric Urban Vehicle
##1. Introduction
This project focuses on optimizing the weight distribution of various components in a hydrogen-powered electric urban vehicle. The goal is to minimize the total weight while accounting for performance contributions of key components, which impact the vehicle's overall efficiency and performance.

##2. Optimization Objectives
The objectives of the optimization are twofold:

Weight Minimization: Reducing the total weight of the vehicle by adjusting component weights within predefined limits.
Performance Contribution: Factoring in the negative performance contribution of each component, where increased weight negatively impacts vehicle performance.
##3. Components and Constraints
The main components considered in the optimization are:

Motor Weight
Fuel Cell Weight
Chassis Weight
Hydrogen Tank Weight
Wheels Weight
Suspension Weight
Transmission Weight
Other Components
Each component has a specified minimum and maximum weight. Additionally, there is a total weight limit for the vehicle that cannot be exceeded.

4. Performance Contribution Factors
Each component has a performance contribution factor that negatively affects the overall vehicle performance. This contribution is modeled using negative values, meaning that heavier components reduce performance. The goal is to minimize both the total weight and the negative impact on performance.

5. Optimization Method
We utilize the Sequential Least Squares Quadratic Programming (SLSQP) optimization method to solve the weight minimization problem. The objective function considers both the total weight and performance contribution factors while adhering to constraints on individual component weights and the total weight limit.

The solution ensures that the vehicle meets the weight constraints and performance requirements while achieving an optimal balance between weight and efficiency.
