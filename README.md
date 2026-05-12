% Define vectors as columns 
v1 = [1; 2; 3]; 
v2 = [2; 4; 6]; 
v3 = [1; 0; 1]; 
% Form matrix 
A = [v1 v2 v3]; 
% Compute rank 
r = rank(A); 
% Number of vectors 
n = size(A,2); 
if r == n 
 disp('Vectors are LINEARLY INDEPENDENT'); 
else 
disp('Vectors are LINEARLY DEPENDENT'); 
end
