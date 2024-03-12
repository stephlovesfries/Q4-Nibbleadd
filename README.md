# Q4-Nibbleadd
## Module 
The specifications for the nibbleadd module are as follows:  
  - Inputs A and B are both 8-bit vector inputs. Output q is 5-bit wide.  
  - When ctrl input is ‘0’, output is the sum of lowest 4 bits of A and B.  
  - When ctrl input is ‘1’, output is the sum of upper 4 bits of A and B.
 
I used the concatenation operator to select the upper or lower 4 bits of A and B, which was subsequently added according to the ctrl conditions, resulting in the output. 
![photo1710204428](https://github.com/stephlovesfries/Q4-Nibbleadd/assets/115708694/ce75b545-34d1-439f-8cba-278085b90482)

## Testbench & Simulation 
Values were assigned to A, B, and ctrl, to check the function of nibbleadd.  
![photo1710204428 (1)](https://github.com/stephlovesfries/Q4-Nibbleadd/assets/115708694/d7b6de94-b27c-4a7a-bc20-45229cac604b)
![photo1710204428 (2)](https://github.com/stephlovesfries/Q4-Nibbleadd/assets/115708694/d72a3e79-f99b-4959-808c-dcf5db1fcd94)
