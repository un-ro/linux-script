# My Collection of shell script
My Spesification:  
![My screenfetch](/asset/screen.png "Screen Fetch")

## Know your shell
### Determine your shell first:  
  - In Terminal ``` echo $0 ```  
  
### To change your shell:  
  1. In Terminal ``` cat /etc/shells ```  
  1. In the first line of script add ``` # !shell-path ```  

### Run Script
  1. Write Script
  1. Set Permission, in Terminal ``` chmod permission_code script_file ```
  1. Run script in Terminal ``` ./script_file ```
  1. Done
  
### (Optional) Setting up PATH:
If you was do step above, you might thinking...  

> Hmm i must running using ./ again  
  
And here I share how to avoid those problem, and in the future you will only  
setting permission only and call file name. Straight!  
  
1. In Terminal ``` export PATH=$PATH:*script_directory* ```. It must be full, example: ``` export PATH=$PATH:~/User/folder/.../folder/main_script ```  
1. Check if it registered, in Terminal ``` echo $PATH ```  
1. If not registered check again no.1  
1. Now you can just have to type ``` hello_world ```. In this case, repo have hello_world script inside.

## Reference  
[Learn Shell](http://linuxcommand.org/lc3_lts0010.php)  
[Unix Permissions Calculator](http://permissions-calculator.org/)  

