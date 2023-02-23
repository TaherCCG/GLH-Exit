

<div align="center">

  #    GLH-Exit

<span style="color:green">Netcom</span> GLH & Exit Tickets

</br>

<p>
My GLH & Exit Tickets stating what I learnt each day.</br>
*Click on date to see full description*

</p>




|     **Date**       |    **Subject**      |        *Breif descritption on subjects covered*               |
|--------------------|---------------------|---------------------------------------------------------------|
|[22/01/23](#w6d3)   | Python              | Python, Debugging, System Admin, Cloud9 Labs, VSCode    |


***
***

</div>

<a id="w6d3"/>
<h5 align="right">Date: 23/01/23</h5>                                                                               
<h5 align="left">Subject: Python Programming</h5>
<p align="justify">Today we continued learning about python. We learnt how to debug and test programs. We made systems admin program that adds a user, deletes user, and adds user groups. We also did labs to debug Caesar cipher that had bugs in it. We used cloud 9 platform and VS. Code to debug the programs. We also learned more in depth about the CI CD process. CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of continuous delivery, and continuous deployment.</p>

Below is a diagram of my understanding of the CI CD and the other CD process.:
<p>Continuous Integration, Continuous Delivery, and Continuous Deployment</p>


```mermaid
graph TD;
    Write.Code-->Submit-->Build.and.Test-->Pass.1?;
    Pass.1?-->Yes.1-->Integrate-->Deploy.to.Staging--Verify-->Pass.2?;
    Pass.2?-->Yes.2-->Manually.Deploy.To.Production-->Smoke.Test;
    Pass.2?-->Yes.2-->Automatically.Deploy.To.Production-->Smoke.Test;
    Smoke.Test-->Release;
    Pass.1?-->No.1-->Write.Code;
    Pass.2?-->No.2-->Write.Code;
    Release-->Yes.2;
    Release-->End.Users;
    Release-->Businesses;
    Release-->Gov;
```
