
# Aero Efficient
### AI-Driven Aerodynamic Prediction and UAV Performance Optimization tool

## Overview
Aero Efficient is an engineering project combining machine learning
and aerodynamic analysis to support faster UAV design exploration which 
reduces time ,effort and cost . 

Website: https://aeroefficient.net/

## Objectives
- Predict lift coefficient (CL) and drag coefficient (CD).
- Estimate aerodynamic efficiency (L/D).
- Explore UAV performance through a performance optimizer.
- Reduce the time required for preliminary aerodynamic analysis.

## Technical Approach
- Data preparation and preprocessing
- Machine-learning model training and evaluation
- Aerodynamic prediction for supported airfoils and wings
- Gradient-based UAV performance optimization

## Technology Stack
- Python
- Machine learning algorithms : [gradient boost for wings datasets , XG-boost regressor for airfoil dataset]
- User interface: [using python streamlit library]
- Aerodynamic tools: [ANSYS Fluent , XFLR5]

## Results and Validation
Report measured model performance 
For wings : CL : Gradient Boost

R2 Score: 0.9703372005139083

MSE: 0.005186140635556057

CD: Gradient boost

R2 Score: 0.9608367668512932

MSE: 3.679891704940347e-06

For airfoils : 
Training CL model...

CL Model - R² Score: 0.9925

CL Model - MSE: 0.0011

Training CD model...

CD Model - R² Score: 0.9528

CD Model - MSE: 0.0000

## Limitations
1) Subsonic regimes (mach 0.02 to 0.3) 
2) cruise conditions (AOA ranging from 0 to 10 degress)
3) 10 airfoils ,their 10 wings
   
## End note
5) This tool could be enhanced by enhancing the datasets ,working on high regimes and adding more airfoils and wings to it 

## Author
Emaan Noor
BS Aerospace Engineering
Institute of Space Technology, Pakistan
