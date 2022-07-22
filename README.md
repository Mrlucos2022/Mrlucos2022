- 👋 Hi, I’m @Mrlucos2022
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Mrlucos2022/Mrlucos2022 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
    <!-- External CSS File -->
    <link rel="stylesheet" href="style.css" type="text/css">

    <!-- Font-Awesome External Link -->
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
    />

    <!-- Google Fonts link -->
    <link href="https://fonts.googleapis.com/css2?family=Alfa+Slab+One&family=Barlow:wght@500;600&family=Blaka+Hollow&family=DM+Sans:wght@400;500;700&family=Nunito:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,800&family=Poppins:wght@300;600&family=Secular+One&family=Source+Sans+Pro:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700;1,900&family=The+Girl+Next+Door&family=Ubuntu:ital,wght@0,700;1,500;1,700&display=swap" rel="stylesheet"
    />
</head>


<body>

    <!-- The Header and Menu start -->
    <div id="header">
        <img src="new.png" alt="sail-logo" id="logo">
        <span id="sailLogo">sail</span>
        <button id="findHelp">Find Help</button>
        <button id="signIn">Sign In</button>
    </div>
    <!-- The Header and Menu end -->


    <!-- Tech Talent Section with Framed Image start     -->
    <div class="about-me">
        <div class="first">
            <h1>I "TechTalent Student" participated in 
                <br> SAIL Intacitive <br> Program.
            </h1>
            <p>The primary purpose of the innovation space is to
                create employment opportunitoes, inspire grass-roots
                innovations and build partnerships & networks that will
                drive economic prosperity and collaboratively solve significant 
                social and business problems.
            </p> 
            <button>Thank You</button>
        </div>
        <img src="frame.png" alt="frame-image">
    </div>
     <!-- Tech Talent Section with Framed Image end     -->


    <!-- Student's group Photo and Senator Abiru Innovation lab section start-->
    <div class="second-section">
        <img src="student.jpg" alt="students-image">
        <div class="sub-second-section">
            <i class="fa-solid fa-quote-left" ></i>  <!--Font awesome Quote symbol-->
            <p>
                SAIL(SENATOR ABIRU INNOVATION LAB) is a unique space that offers cross-functional programmes
                and opportunities as well as a basic foundation that can inspire young people in Lagos East (students,
                graduates, entrepreneurs, job seekers) to gather, learn and create. The space will faster a comfortable
                and safe environment that will encourage young people to see it as their second home.
            </p>
            <br>
            <span>
                Senator Tokunbo Abiru of the Lagos East 
                <br> 
                Constituency,  <i  class="fa-solid fa-quote-right"></i> <!--Font awesome Quote symbol-->
            </span>          
        </div>
    </div>
      <!-- Student's group Photo and Senator Abiru Innovation lab section end-->

    
    
    <div class="container">

        <!-- Call, Messsage and Location section start -->
        <div class="container2">
            <div class="child">
                <div class="child-about-container">
                    <i class="fa-solid fa-phone"></i> <!--Font awesome Phone symbol-->
                    <div class="child-about">
                        <p class="child-about1">Give us a call</p>
                        <p class="child-about2">0809 393 4546</p>
                    </div>
                </div>
                <div class="child-about-container">
                    <i class="fa-solid fa-envelope"></i> <!--Font awesome envelope symbol-->
                    <div class="child-about">
                        <p class="child-about1">Send us a message</p>
                        <p class="child-about2">info@sailnigeria </p>
                    </div>
                </div>
    
                <div class="child-about-container">
                    <i class="fa-solid fa-location-dot"></i> <!--Font awesome location symbol-->
                    <div class="child-about">
                        <p class="child-about1">Office Location</p>
                        <p class="child-about2"> 68 TOS Benson Rd, Ikorodu 104101, Ikorodu</p>
                    </div>
                </div>
            </div>
        </div>
        <!-- Call, Messsage and Location section end -->
      
        <!-- Footer section start -->
        <div class="container3">
            <div>
                <div class="footer-logo">
                    <img class="logo" src="new.png" />
                    <h3 class="logo-header">sail</h3>
                </div>
                <br>
    
                <div class="footer-icons">
                    <i class="fa-brands fa-facebook-f"></i> <!--Font awesome Facebook symbol-->
                    <i class="fa-brands fa-twitter"></i> <!--Font awesome Twitter symbol-->
                    <i class="fa-brands fa-instagram"></i> <!--Font awesome Instagram symbol-->
                    <i class="fa-brands fa-linkedin-in"></i> <!--Font awesome LinkedIn symbol-->
                </div>
            </div>
            <div class="footer3">
                <p class="anchor-header">Company</p>
                <a href="#">About</a>
                <a href="#">Careers</a>
                <a href="#">FAQ</a>
                <a href="#">Privacy Policy </a>
            </div>
            <div class="footer">
                <p class="anchor-header">Get help</p>
                <div class="footer-anchor">
                    <a href="#">Request emergency </a>
                    <a href="#">Find a support group </a>
                </div>
            </div>   
        </div>
          <!-- Footer section end -->

    </div>
</body>
</html>

Css.html👇👇👇
/* General Styling */

*{
    padding: 0rem;
    margin: 0rem;
}

body{
    background-color: #F5F5F5;
}



/* The Header and Menu start */

#header {
    background-color:rgba(254, 255, 255, 1);
    width: 100%;
    height: 60px;
}

#logo{
    width: 4rem;
    height: 2rem;
    margin: 10px 0px 0px 60px;
}

#sailLogo{
    font-family: 'DM Sans', sans-serif;
    font-style: normal;
    font-weight: 700;
    font-size: 30.963px;
    margin: 0px 0px 0px 0px;
    letter-spacing: -0.065em;
    color: #3958A7;

}

#findHelp{
    float: right;
    margin: 10px 50px 0px 0px;
    height: 2.1rem;
    width: 6rem;
    border-radius: 4.98px;
    border: 1px solid #0134B7;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    color: rgba(51, 51, 51, 0.4);
}

#signIn{
    float: right;
    width: 6rem;
    height: 2.1rem;
    color: #fff;
    background-color:#3958A7;
    border-radius: 4.98px;
    margin: 10px 40px 0px 0px;
    border: none;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
}
/* The Header and Menu end */



/*  Tech Talent Section with Framed Image start      */

.first{
    width: 27%;
    margin: 50px 0px 0px 80px;
}

.first h1{
    line-height: 50px;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 2em;
}
.first p{
    line-height: 23px;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 15.4961px;
    color: #000000A6;

}

.first button{
    background-color:#3958A7;
    padding: 7px 90px 7px 7px;
    margin-top: 15px;
    color: #fff;
    border-radius: 4.98px;
    border: none;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
}

.about-me img{
    width: 25%;
    height: 20rem;
    float: right;
    margin: -22rem 20rem 0px 0px;
}

/* Tech Talent Section with Framed Image end */



/* Student's group Photo and Senator Abiru Innovation lab section start */

.second-section{
    background-color:rgba(234, 225, 16, 0.06);
    height: 30rem;
    margin-top: 5rem;
}

.second-section img{
    width: 40%;
    margin: 4rem 0rem 0rem 5rem;
    height: 23rem;
}

.sub-second-section{
    float: right;
    width:35%;
    margin: 3rem 10rem 0rem 0rem;
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 15.4961px;
    line-height: 30px;
    color: #000000;
}

.fa-solid{
    padding: 36px 15px 0 0;
    color: #0055A3;
}

.fa-quote-left{
    font-family: 'Arial';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 225px;    
    color: rgba(14, 14, 14, 0.18);
}


.sub-second-section span{
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    color: #2752BF;
}

.fa-quote-right{
    font-family: 'Arial';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 225px;
    padding-top: 8px;
    padding-right: 5px;
    color: rgba(14, 14, 14, 0.18);
    float: right
}
/* Student's group Photo and Senator Abiru Innovation lab section end */






.container{
    box-sizing: border-box;
    width: auto;
    width: 100%;
    margin: 0 auto;
    border-radius: 5px;
}




 /* Call, Messsage and Location section start  */

.container2{
    display: flex;
    justify-content: space-around;
    padding-top: 30px;
   margin: 0px 1px 0 1px;
   position: relative;
   background: rgba(234, 225, 16, 0.06);
   padding-bottom: 10px;
}

.child {
    height: 78px;
    background: #F9F9F9;
    box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.03);
    width: 70%;
    position: absolute;
    top: 5px;
    left: 200px;
    display: flex;
  }

.child-about-container{
      display: flex;
      margin: 0 auto;
      justify-content: space-between;

  }

.child-about{
     margin-top: 30px;
  }



.child-about1{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 10px;
    line-height: 145.5%;
    color: #000000;
    opacity: 0.38;
    margin: 0;

  }

.child-about2{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 10px;
    line-height: 18px;
    margin: 0;
    color: rgba(0, 0, 0, 0.75);
  }

  /* Call, Messsage and Location section end  */





 /* Footer section start  */

.container3{
    background: #F5F5F5;
     display: flex;
     justify-content: space-around;
     padding-top: 150px;
     padding-bottom: 100px;
  }
.footer-logo{
    display: flex;
    width: 80%;
  }

.logo{
    width: 61px;
   height: 36.12px;
}

.logo-header{
   font-family: 'DM Sans', sans-serif;
   font-style: normal;
   font-weight: 700;
   font-size: 30.963px;
   margin-top: 0;
   letter-spacing: -0.065em;
   color: #3958A7;
}


.footer-icons{
      display: flex;
      justify-content: space-between;
      height:35px
  }

  .fa-brands{
    background: #FFFFFF;
    color: #0055A3;
    padding: 9px;
    margin-right: 13px;
    border-radius: 16px;
    box-shadow: 0px 8.5923px 11.897px rgba(17, 19, 35, 0.08);
}

  .footer3{
      width: 4%;
  }

  .footer{
      width: 9%;
  }

  .anchor-header{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 12.1147px;
    line-height: 18px;
    color: #00A347;
  }

 .footer-anchor{
     padding-top: 28px;
 }

a{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 10px;
    text-decoration: none;
    color: rgba(0, 0, 0, 0.6);
    
  }

   /* Footer section end  */




_____&______&&&&&&______________&&&&&&&&____

Skip to content
Sign up
PyLaizer
/
API-Project-Dictionary
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
API-Project-Dictionary/Dictionary/css/style.css
@PyLaizer
PyLaizer Add files via upload
 1 contributor
114 lines (99 sloc)  2.21 KB
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background: linear-gradient(90deg, rgba(65,9,121,0.7)50%, rgba(0,212,255,0.7)100%);
}

.head{
    text-align: center;
    font-family: 'Poppins', sans-serif;
    color: whitesmoke;
    font-weight: 800;
}

.container{
    background-color: white;
    width: 500px;
    border-radius: 10px;
    margin: 30px auto;
    padding: 60px 50px;
}

.search_box{
    display: flex;
    width: 100%;
    justify-content: space-between;
}

.search_box input{
    padding: 5px;
    width: 70%;
    border: none;
    outline: none;
    border-bottom: 3px solid rgba(65,9,121,0.7);
}

.search_box button{
    width: 25%;
    background:linear-gradient(90deg, rgba(65,9,121,0.7)50%, rgba(0,212,255,0.7)100%) ;
    color: whitesmoke;
    padding: 15px 0;
    border-radius: 10px;
    font-family: 'Josefin Sans', sans-serif;
    font-size: 20px;
    font-weight: 500;
    border: none;
}

.search_box button:hover{
    background: linear-gradient(90deg, rgba(65,9,121,1)50%, rgba(0,212,255,1)100% );
}

.result{
    position: relative;
}

.result h3{
    font-size: 50px;
    color: rgba(65,9,121,0.7);
    font-family: 'Poppins', sans-serif;
    font-weight: 800;
}

.result .word{
    display: flex;
    justify-content: space-between;
    margin-top: 40px;
}

.result .details{
    display: flex;
    gap: 10px;
    color: rgba(0,212,255,1);
    margin: 5px 0 20px 0;
    font-size: 20px;
    font-family:'Poppins', sans-serif ;
    font-weight: 300;
}

.word_meaning{
    color: rgba(65,9,121,0.7);
    font-family: 'Josefin Sans', sans-serif;
    font-weight: 400;
    font-size: 23px;
}

.example{
    margin-top: 30px;
    font-size: 20px;
    font-family: 'Josefin Sans', sans-serif;
    font-weight: 300;
    color: rgba(0,212,255,0.7);
    margin-bottom:0;
}

.word_example{
    color: rgba(65,9,121,1);
    font-style: italic;
    border-left: 5px solid rgba(0,212,255,1);
    font-family:'Poppins', sans-serif;
    font-weight: 500;
    margin-top: 10px;
    font-size: 23px;
    padding-left: 20px;
}

.error{
    text-align: center;
    margin-top: 80px;
    border: 2px solid red;
}







<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css" type="text/css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500&family=Poppins:wght@300;500;800&display=swap" rel="stylesheet">
</head>
<body>
    <h1 class="head">My Dictionary</h1>
    <div class="container">
        <div class="search_box">
            <input type="text" placeholder="Type your word here.." id="input_word">
            <button id="search_button">Search</button>
        </div>
        <div class="result" id="result">
            
        </div>
    </div>
    <script src="js/main.js"> </script>
</body>
</html>






const Url = "https://api.dictionaryapi.dev/api/v2/entries/en/";
const Result = document.getElementById("result");
const Btn = document.getElementById("search_button");

Btn.addEventListener("click", () => {
    let Inputword = document.getElementById("input_word").value;
    fetch(`${Url}${Inputword}`).then((response) => response.json()).then((data) => {
        console.log(data);
        Result.innerHTML = `
        <div class="word">
            <h3>${data[0].word}</h3>
        </div>
        <div class="details">
            <p>${data[0].meanings[0].partOfSpeech}</p>
            <p>${data[0].phonetic}</p>
        </div>
            <p class="word_meaning">
               ${data[0].meanings[0].definitions[0].definition}
            </p>
            <p class="example">Example</p>
            <p class="word_example">
                ${data[0].meanings[0].definitions[0].example || ""}
            </p>
        `
    }).catch(() => {
        Result.innerHTML = `<h3 class="error">Couldn't Find The Word</h3>`
    })
})




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>The Fifth character in the string is :<span id="s1"></span></p>
    <p>The Two values are : <span id="s2"></span></p>
    <p>The Additon of the two numbers is :<span id="s3"></span></p>
    <p>The Type of our value is : <span id="s4"></span></p>
    <p>The first three characters in the string are : <span id="s5"></span></p>
    <p>The last three characters in the string are : <span id="s6"></span></p>
    <p>The characters in the string are : <span id="s7"></span></p>
    <p>The first half and the second half of the string is : <span id="s8"></span><span id="s9"></span></p>
    <p>Is the number an even digit : <span id="s10"></span></p>
    <p>The average of the array : <span id="s11"></span></p>
    <script src="main.js"></script>
</body>
</html>




/
JavaScript-Beginners-Coding-Challenges

//1. Write a function that takes a string and a number and then gives the nth character that string.
function charfunction($string, $val){
    // let $arr = $string.split("")
    // let $specarr = $arr[$val - 1]
    // document.getElementById("s1").innerHTML = $specarr

    let result = $string.charAt($val - 1)
    document.getElementById("s1").innerHTML = result;

}
charfunction("JavaScript",5)

//2. Write a function to compare two numbers: Must be of equal value and type
function compareFunction(x,y){
    if( x === y){
        return true
    }else{
        return false
    }
}

document.getElementById("s2").innerHTML = compareFunction(81,"81")

//3. Addition of two numbers
function addFunction(val1,val2){
    let $result = val1 + val2;
    document.getElementById("s3").innerHTML = $result

}

addFunction(24,32)

//4. A funtion to return the type of a value
function typeFunction(value){
    let $result = typeof(value)
    document.getElementById("s4").innerHTML = $result
}

typeFunction(["a","b",90])

// 5. A function that retuns the first three characters in a string
function retThreeFunction(x){
    let $result;
    $result = x.slice(0,3)
    document.getElementById("s5").innerHTML = $result
}

retThreeFunction("Nigeria")

//6. A function that retuns the last three characters in a string
function retLastThreeFunction(y){
    let $result;
    $result = y.slice(-3,)
    document.getElementById("s6").innerHTML = $result
}

retLastThreeFunction("Nigeria")

//7. A function that return a specified no characters
function myFunction($str,f_index,l_index){
    let $result;
    $result = $str.slice(f_index,l_index)
    document.getElementById("s7").innerHTML = $result
}

myFunction("metropolitant",3,8)  

//8. A function that will return half of an entire string; expected outcome: compe

function halfFunction(str){
    let f_index,l_index,str_len,result,result2;
    str_len = str.length
    f_index = 0;
    l_index = str_len / 2 //5
    result = str.slice(f_index,l_index);

    document.getElementById("s8").innerHTML = result;

    result2 = str.slice(l_index, )
    document.getElementById("s9").innerHTML = result2;

}

halfFunction("abcdefghijklmnopqrstuvwxyz")

//9. A function to check for even number
function evenFunction(x){
    let $result = x % 2
    if($result == 0){
        return true
    }else{
        return false
    }
}

document.getElementById("s10").innerHTML = evenFunction(12)

//10. A function that returns the avarage no in an array
function avgFunction(x){
    let $sum,$arr_length,$result,y;
    $sum = 0;
    for(y of x ){
        $sum += y;
    }
    $arr_length = x.length
    $result =  $sum / $arr_length
    return $result
}
document.getElementById("s11").innerHTML = avgFunction([2,3,4,5,6,7])

