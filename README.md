# RESUME-GENERATER-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="style.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    
    <link rel="stylesheet" href="style.css" />

       <title">Resume Generator</title>

              
</head>
<body>

<div class="Container" id="cv-form">
        <h1 class="text-center my-4">Resume Generator</h1>
        <p class="text-center">By Epsa Sharma (◔‿◔)</p>

        <div class="row">
          <div class="col-md-6 mx-5">  
                 <h3>Personal Information</h3>

                <div class="form-group mt-2 mx-5">
                        <label for="Firstname"> Name</label>
                        <input type="text" 
                        id="Name" 
                        Placeholder="Enter Here" 
                        class="form-control" 
                        />
                </div>
               
                
                <div class="form-group mt-2 mx-5">
                        <label for="DOB">DOB</label>
                        <input type="text" 
                        id="DOB" 
                        Placeholder="Enter here" 
                        class="form-control" 
                        />
                </div>



                <div class="form-group mt-2 mx-5">
                        <label for="contactdetail">Your Contact Numbers</label>
                        <input type="text" 
                        id="contactdetails" 
                        Placeholder="Enter here" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="EmailID">Your Email ID</label>
                        <input type="text"
                         id="EmailID" 
                        Placeholder="Enter your email here" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="AddressField">Your Address</label>
                        <textarea
                        id="AddressField" 
                        Placeholder="Address where you are living since 1 year" 
                        class="form-control" 
                        ></textarea>
                </div>

                <p class="text-secondary mt-2 my-3 mx-5">Important Links</p>

                <div class="form-group mt-2 mx-5">
                        <label for="FBField">Facebook</label>
                        <input type="text"
                         id="FBField" 
                        Placeholder="Facebook account Link" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="InstaField">Instagram</label>
                        <input type="text"
                         id="InstaField" 
                        Placeholder="Instagram account Link" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="TwitField">Twitter</label>
                        <input type="text" 
                        id="TwitField" 
                        Placeholder="Twitter account Link" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="LinkinField">LinkedIn</label>
                        <input type="text" 
                        id="LinkinField" 
                        Placeholder="LinkedIn account Link" 
                        class="form-control" 
                        />
                </div>

                <div class="form-group mt-2 mx-5">
                        <label for="GithubField">Github</label>
                        <input type="text" 
                        id="GithubField" 
                        Placeholder="Github account Link" 
                        class="form-control" 
                        />
                </div>


          </div>
          <div class="col-md-6 my-5 mx-5"> 
                  
                <!--2nd column-->

                <h3>Objective</h3>
                
                <div class="form-group mt-2 my-5 mx-5">
                        <label for="objective"></label>
                        <textarea
                        id="Objective" 
                        Placeholder="Enter Here" 
                        class="form-control"
                        
                        ></textarea>
                </div>

                
                
                <div class="col-md-6  mt-4 mx-5">
                        <h3>Educational Details</h3>
                        <div class="form-group mt-4 my-3" id="eq">
                              <label for="EdDetails">Qualification and Discription</label>                        
                        <textarea
                        id="EdDetails" 
                        Placeholder="Enter Here" 
                        class="form-control eqField"
                        
                        ></textarea>
      
                            
      
                      <div class="container text-center mt-3" id="eqAddButton">
                              <button onclick="AddEDField()" class="btn btn-primary btn-sm">Add</button>
                      </div>
                      </div>
      
                   
      
                </div>
       
                
          <div class="col-md-6  mt-4 mx-5">
           
                <h3>Project Details</h3>
                  <div class="form-group mt-4 my-3" id="pj">
                        <label for="Project1">Project Title and Discription</label>
                        <textarea
                        placeholder="Enter Here"
                        class="form-control pjField"
                        ></textarea>
                

                      

                <div class="container text-center mt-3" id="pjAddButton">
                        <button onclick="AddPJField()" class="btn btn-primary btn-sm">Add</button>
                </div>
                </div>

             

          </div>

          
          <div class="col-md-6 mt-4 mx-5">
                <h3>Certifications</h3>
                  <p class="text-secondary my-3 mx-5">Any 4 Certifications</p>

                  <div class="form-group mt-2 my-4" id="ct">
                          <label for="Certificate1"></label>
                          <textarea
                          id="Certificate1"
                          placeholder="Enter here"
                          class="form-control ctField"
                          ></textarea>

                          <!---next textarea-->

              
                  <div class="container text-center mt-3 " id="ctAddButton">
                                <button onclick="AddNewCTField()" class="btn btn-primary btn-sm">Add</button>
                               
                        </div>
                </div>
             
                
          </div>
          

          <div class="col-md-6 mt-4 mx-5">
             
                <h3>Experiance</h3>
                
                <div class="form-group mt-2 my-4" id="we">
                        <label for="Experiance"></label>
                        <p  >Add Institute name, Profession and Duration</p>
                        <textarea
                        placeholder="Enter Here"
                        class="form-control weField"
                        ></textarea>
                
                        <div class="container text-center mt-3" id="weAddButton">
                                <button onclick="AddNewWEField()" class="btn btn-primary btn-sm">Add</button>
                        </div>
                </div>
                        
                </div>

                
          </div>
          <div class="container text-center mt-3 my-5">
                <button onclick="generateCV()" class="btn btn-primary btn-lg"> Generate Resume</button>
        </div>

</div>

<!--Cv Template-->

<div class="container" id="CV-template">

        <div class="row">

               <div class="col-md-4 py-5 background">

                <!--first column-->
                <img src="https://moonvillageassociation.org/wp-content/uploads/2018/06/default-profile-picture1.jpg"
                alt=""
                class="img-fluid myimg"
                
                />
               
                <div class="container">

                        <hr/>
                        <h2>About Me:</h2>
                        <p id="nameT1">Name: Epsa Sharma</p>
                        <p id="dobT">DOB: 21-7-2003</p>

                        <hr/>
                        <h2>Contact Details</h2>
                        <p id="contactT">Contact Number : +91-6789304528, +91-5679340862</p>
                        <p id="addressT">Address: 67899/34567 Sector 24, Noida, Delhi, India</p>
                        <p id="emailT">EMail ID: epsa3546@gmail.com</p>

                        <hr/>

                        <h2>Skills</h2>
                        <p >1. Effective Listening and Effective Oral listening Skills.</p>
                        <p >2. Great atproblem solving.</p>
                        <p >3. Ability to Quickly Create and apply ideas.</p>
                        <p >4. Good Leadership Skills.</p>
                        <p >5. Critical Thinker.</p>
                        

                        <hr />

                        <p id="fbT"><a href="#1">https://www.facebook.com/Epsa</a></p>
                        <p id="instaT"><a href="#1">https://www.instagram.com/sergam.10</a></p>
                        <p id="twT"><a href="#1">https://www.twitter.com/Sergam08</a></p>
                        <p id="linkT"><a href="#1">https://www.linkedin.com/in/epsa-sharma-019324230</a></p>
                        <p id="GithubT"><a href="#1">https://github.com/20BCS4485</a></p>
                </div>
                
               </div>

               <div class="col-md-8 py-5">

                <!--2nd column-->
                <h1 id="nameT2" class="text-center" style="font-weight: 980">Epsa Sharma</h1>

                <!--Objective Cards-->

                <div class="card mt-4">
                        <div class="card-header background">
                            <h3>Career Objective</h3>    
                        </div>
                        <div class="card-body">
                                <p id="ObjT">
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque possimus repudiandae
                                         voluptas beatae voluptatibus dolor ipsam deleniti nihil maiores odio itaque numquam
                                          consequatur, est fugiat. Sunt deserunt eaque maxime culpa, pariatur ipsam aliquid
                                           necessitatibus, ratione voluptas facere ullam nobis. Eos dignissimos fugiat soluta
                                            maxime voluptatibus autem cupiditate nulla laborum animi?
                                </p>
                        </div>
                </div>

                <!--Educational Details-->

                <div class="card mt-4">
                        <div class="card-header background">
                            <h3>Educational Details</h3>    
                        </div>
                        <div class="card-body">
                                <ul id="edT">
                                        <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt quidem magni hic quas consequuntur tempore vero iste rem saepe consectetur!</li>
                                </ul>
                                
                        </div>
                </div>
                <!-- Project Details-->
                <div class="card mt-4">
                        <div class="card-header background">
                            <h3>Projects Details</h3>    
                        </div>
                        <div class="card-body">
                                <ul id="pT">
                                        <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt quidem magni hic quas consequuntur tempore vero iste rem saepe consectetur!</li>
                                </ul>
                               
                        </div>
                </div>

                <!--Certifications-->
                <div class="card mt-4">
                        <div class="card-header background">
                            <h3>Certifications</h3>    
                        </div>
                        <div class="card-body">
                                <ul id="ctT">
                                        <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt quidem magni hic quas consequuntur tempore vero iste rem saepe consectetur!</li>
                                </ul>
                               
                        </div>
                </div>

                <div class="card mt-4">
                        <div class="card-header background">
                            <h3>Experiance</h3>    
                        </div>
                        <div class="card-body">
                                <ul id="weT">
                                        <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt quidem magni hic quas consequuntur tempore vero iste rem saepe consectetur!</li>
                                </ul>
                              
                        </div>
                </div>

                <div class="container mt-4  text-center">
                        <button onclick="printCV()" class="btn background btn-lg">Print Resume</button>
                </div>

               </div>
        </div>
</div>

        


       
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
     <script src="script.js"></script>

</body>
</html>

function AddNewCTField(){
    // console.log("Adding data");
 
     let newNode= document.createElement('textarea');
     newNode.classList.add('form-control');
     newNode.classList.add('ctField');
     newNode.classList.add('mt-3');
     newNode.setAttribute('placeholder','Enter Here');
 
     let ctOb=document.getElementById('ct');
     let ctAddButtonOb=document.getElementById('ctAddButton');
 
     ctOb.insertBefore(newNode, ctAddButtonOb);
 
 }
 
 function AddNewWEField(){
     let newNode= document.createElement('textarea');
     newNode.classList.add('form-control');
     newNode.classList.add('weField');
     newNode.classList.add('mt-3');
     newNode.setAttribute('placeholder','Enter Here');
 
     let weOb=document.getElementById('we');
     let weAddButtonOb=document.getElementById('weAddButton');
 
     weOb.insertBefore(newNode, weAddButtonOb);
 
 
 }
 
 function AddPJField(){
  
     let newNode= document.createElement('textarea');
     newNode.classList.add('form-control');
     newNode.classList.add('pjField');
     newNode.classList.add('mt-3');
     newNode.setAttribute('placeholder','Enter Here');
 
     let pjOb=document.getElementById('pj');
     let pjAddButtonOb=document.getElementById('pjAddButton');
 
     pjOb.insertBefore(newNode, pjAddButtonOb);
 
 
 }
 
 function AddEDField(){
  
     let newNode= document.createElement('textarea');
     newNode.classList.add('form-control');
     newNode.classList.add('eqField');
     newNode.classList.add('mt-3');
     newNode.setAttribute('placeholder','Enter Here');
 
     let eqOb=document.getElementById('eq');
     let eqAddButtonOb=document.getElementById('eqAddButton');
 
     eqOb.insertBefore(newNode, eqAddButtonOb);
 
 
 }
 
 //generating CV
 function generateCV(){
     //console.log("Generating CV");
 
     let Name= document.getElementById('Name').value;
     
     let nameT1= document.getElementById('nameT1');
       
     nameT1.innerHTML= Name;
 
     //direct
     document.getElementById("nameT2").innerHTML = Name;
 
     //DOB 
 
     let DOB= document.getElementById('DOB').value;
     let dobT= document.getElementById('dobT');
     dobT.innerHTML= DOB;
 
     //contact
 
     document.getElementById("contactT").innerHTML=document.getElementById("contactdetails").value;
     
     //Email ID
 
     document.getElementById("emailT").innerHTML=document.getElementById("EmailID").value;
 
     //address
 
     document.getElementById("addressT").innerHTML=document.getElementById("AddressField").value;
 
     //important links
 
     document.getElementById("fbT").innerHTML=document.getElementById("FBField").value;
     document.getElementById("instaT").innerHTML=document.getElementById("InstaField").value;
     document.getElementById("twT").innerHTML=document.getElementById("TwitField").value;
     document.getElementById("linkT").innerHTML=document.getElementById("LinkinField").value;
     document.getElementById("GithubT").innerHTML=document.getElementById("GithubField").value;
 
     //career Objective
     document.getElementById('ObjT').innerHTML=document.getElementById("Objective").value;
 
 
     
     //work Experience
 
     let wes= document.getElementsByClassName('weField');
     let str='';
 
     for(let e of wes)
 {
     str = str +`<li> ${e.value} </li>`;
 }
     document.getElementById('weT').innerHTML= str;
 
     // Educational Details
     let eqs= document.getElementsByClassName("eqField");
 
     str1='';
     for(let e of eqs){
         str1 = str1 + `<li> ${e.value} </li>`;
     }
 
     document.getElementById('edT').innerHTML= str1;
 
     //Certification
 
     let cs= document.getElementsByClassName("ctField");
 
     str2 = '';
     for (let e of cs){
         str2= str2 + `<li> ${e.value} </li>`;
     }
 
     document.getElementById('ctT').innerHTML =str2;
 
    //project 
    let ps=document.getElementsByClassName("pjField");
    str3='';
    for(let e of ps){
        str3= str3+ `<li> ${e.value} </li> `;
    }
     document.getElementById('pT').innerHTML= str3;
 
     document.getElementById('cv-form').style.display='none';
     document.getElementById('CV-template').style.display='block';
 
 }
 function printCV(){
     window.print();
 }
body{
    background-color: bisque;
  }

  #cv-form{
    /*display : none; */
  }
  #CV-template{
    display : none; 
  }
  
  .myimg{
    border: 1px solid black;
    border-radius: 50% ; 
    width: 200px ;
  }

  .background{

    background-color: silver;
  }

