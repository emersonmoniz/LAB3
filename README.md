LAB 3 answers
1. ###MSE my network: **11.15**
   ###MAE my network: **2.5060**

   ###MSE Linear Regression: **24.29**

   ###MSE 128 my network: **16.42** with 128 neurons
   ###MAE 128 my network: **2.7672** with 128 neurons
3. Resulting size(2x2) 
4. Output size = O (99,99)
   Conv 2_24 = (2,2,3) *24 = 288
   Stacking smaller (3x3) kernels is more efficient than stacking a large kernel(7x7) because it allows on the VGG to have a deeper layer and take advantage of allowing more non-linear layers in between which serves best for discrimination. Decreases the number of parameters, assuming the same number of channels. It decreases the parameterization by 81%. It has a larger cost in memory. 
   P=(O(s-1)-s+F)/2
