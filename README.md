# javascript_interview_questions
This is a repo which i was following " Interview Happy" (https://www.youtube.com/watch?v=AUTO7ALJk2U) channel to sharpen my knowledge. Find 100 question and practicing the answers. 

# Q1 -  What is Javascript ? What is the role of JS engine ?
    JavaScript is a programming language that isused for converting static web pages to interactive and dynamic web pages

![alt text](image.png)

    As shown in above picture, every browser it has an JavaScript engine inbuilted. this engine is a program present in web browser that execute JavaScript code. Internaly the respond from the server of JS code executed by these engine on the front-end.

# Q2 - What are Client side and Server site ?
    A Client is a devise, application, or software component that requests and consumes services or resources froma Server.
    A Server is a devise, computer, or software application that provides services, resources, or functions to clients.

# Q3 - What is Scope in JavaScript ?
    //Global Scope - Accessible anywhere
    let globalVariable = "global"

    greet()

    function greet(){
        //Function scope - accessible inside function only 
        let functionVariable = "function"

        if(true){
            //Block scope - Accessible inside block only
            let blockVariable = "block"
        }
    }
