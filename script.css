    
 const rockbtn=document.querySelector("#rock");
  const paperbtn=document.querySelector("#paper");
  const scissorbtn=document.querySelector("#scissor");
  var player_score=document.querySelector(".player");
   var computer_score=document.querySelector(".computer");
  const text = document.querySelector(".outcome");
  
 
  function getComputerChoice(){
    const choices =["rock","paper","scissors"];
 const choice =Math.floor(Math.random()*choices.length);
    return choices[choice];
    
  }
  
  
  
  rockbtn.addEventListener("click",()=>{
    rockbtn.classList.add("clicked");
   setTimeout(()=>{rockbtn.classList.remove("clicked"); },500)
    
;

   const computer_choice= getComputerChoice();
    
    if(computer_choice==="paper"){
    text.innerHTML= `You lose! ${computer_choice} beats rock`;
      computer_score.innerHTML=parseInt(computer_score.innerHTML)+1;
    }else if (computer_choice=== "scissors"){
      text.innerHTML= `You win! rock bears ${computer_choice}`;
       player_score.innerHTML=parseInt(player_score.innerHTML)+1;
    }else{
      text.innerHTML="Its a tie";
    }
  });
  scissorbtn.addEventListener("click",()=>{
    scissorbtn.classList.add("clicked");

   setTimeout(()=>{scissorbtn.classList.remove("clicked"); },500)

    

;
   const computer_choice= getComputerChoice();
    
    if(computer_choice==="rock"){
    text.innerHTML= `You lose! ${computer_choice} beats scissors`;
      computer_score.innerHTML=parseInt(computer_score.innerHTML)+1;
    }else if (computer_choice=== "paper"){
      text.innerHTML= `You win! scissors beats ${computer_choice} `;
       player_score.innerHTML=parseInt(player_score.innerHTML)+1;
    }else{
      text.innerHTML="Its a tie";
    }
  });
  paperbtn.addEventListener("click",()=>{
    paperbtn.classList.add("clicked");
   setTimeout(()=>{paperbtn.classList.remove("clicked"); },500)
    
;
   const computer_choice= getComputerChoice();
    
    if(computer_choice==="scissors"){
    text.innerHTML= `You lose! ${computer_choice} beats paper`;
      computer_score.innerHTML=parseInt(computer_score.innerHTML)+1;
    }else if (computer_choice=== "rock"){
      text.innerHTML= `You win! paper beats ${computer_choice} `;
       player_score.innerHTML=parseInt(player_score.innerHTML)+1;
    }else{
      text.innerHTML="Its a tie";
    }
  });
