# Submission

1. Create VM on azure:  
    Region: (Europe) UK South  
    Inbound ports HTTP, HTTPS, SSH
![](images/01_createVM.png)
2. Check VM Overview
![](images/02_VM_overview.png)
3. Add Inbound Role (changed this to port 4000 later)
![](images/03_Add_inbound_rule.png)

NOTE! The VM got deleted before I could move on to thi next step, did the above steps again and then proceeded with the following steps.  
4. SSH into VM

5. sudo apt install java  
![](images/04_ssh_intoMachine.png)

6. Copied over jar file  
![](images/06_copiedOverJar.png)

6. Run Java on VM  
![](images/07_runJavaJar.png)