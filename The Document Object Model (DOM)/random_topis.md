RANDOM TOPICS:

Add Event Listener:

        var butt=document.querySelectorAll(".drum");
        for(var i=0;i<butt.length;i++){
            butt[i].addEventListener("click",popp);
        }
        
        function popp(){
            alert("hello");
        }
        // This pops alert when we click on button

High order function: using and calling fuction in another function

      function add(a,b){
        return a+b;
        }
        function mul(a,b){
        return a*b;
        }
        function calc(a,b,operator){
        return operator(a,b);
        }

        calc(3,4,mul);

        o/p:

        12

debugger: shows the each and every step of execution to find what is going wrong

      debugger;
      calc(2,5,add);

         
