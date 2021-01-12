## Savchyn_S. EPAM DevOps courses. TASK_2.1. Work with VirtualBox

### what are the most popular hypervisors for infrastructure virtualization?

Linux KVM
Microsoft Hyper V
VMware
Oracle VirtualBox

### briefly describe the main differences of the most popular hypervisors.

there are two types of hypervisors.
Type 1: hypervisors run directly on the system hardware – A “bare metal” embedded hypervisor,
Type 2: hypervisors run on a host operating system that provides virtualization services, such as I/O device support and memory management.

cloned VM1 and made a snapshot  
![image2_1](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_1.png)
	
connected USB  
![image2_2](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_2.png)

configured shared folder  
![image2_3](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_4.png)

configured connection between VM1 and VM2  
![image2_4](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_7.png)

work with CLI through VBoxManage  
![image2_5](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_8.png)

cloned VM2 through VBoxManage  
![image2_6](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_9.png)

checked Vagrant PATH variable  
![image2_7](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_10.png)

initialized environment with default vagrant box  
![image2_8](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_11.png)

connected to VM using PuTTY  
![image2_9](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_12.png)

created own Vagrant box and configured ssh keys  
![image2_10](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_16.png)

checked sshd status  
![image2_11](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_17.png)
	
packaged, added and initialised own Vagrant box  
![image2_12](https://github.com/xwav/epam_lectures_devops_Savchyn_2020/blob/main/Lecture_2/Task_2.1/images/task2_20.png)





