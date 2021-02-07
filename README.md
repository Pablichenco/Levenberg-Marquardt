# Levenberg-Marquardt
Levenberg-Marquardt method is used to solve non-linear least squares problems, especially in least squares curve fitting.Here we use the lapack library in Accelerate.framework in order to solve the equation Ax=b for a symmetric positive-definite matrix A, with A in this LM method the Hessian h.
 
The LMA is more robust than the GNA, which means that in many cases it finds a solution even if it starts very far off the final minimum.

Note: IMPORTANT!! You should commpile the code on Xcode with the lapack library linked to the project otherwise you should modifi the file to run in a no-Xcode enviroment
