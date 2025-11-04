# Navigate to VPC to create a private subnet

1. create a private subnet, without public IP assignment, settings like image, scroll to the bottom, click **Create subnet**
![Alt text](image1.png)

2. successfully
![Alt text](image2.png)

3. create a ec2 instance named "Bastion host" in "public-subnet-02", and a ec2 instance in "private-subnet-02" with the settings like below
![Alt text](images/image3.png)
![Alt text](image4.png)


4. create a NAT instance, with the settings like below
![Alt text](image5.png)


5. turn off the "Change Source/ destination check" of the **Nat instance**
![Alt text](./image6.png)


6. create "private-route-table-02", in the "subnet association", add "private-subnet-02", with the route like below
![Alt text](./image7.png)
