
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>survey-form</title>
</head>
<body>
  <div class="heading">
  <h1 id="head">freecodecamp Survey Form </h1>
  <h2 id="subheading"><i>Thank you for taking the time to help us improve the plateform</i></h2>
    </div>
    <div id="content1">
        <label>Name</label><br><b>
        <input type="name"  name="name" placeholder="Enter your name" class="box"> <br><br>
        <label>Email</label>  <br><br>
        <input type="email" name="email"placeholder="Enter your email" class="box"><br><br>
        <label>Age(optional) </label><br><br>
        <input type="age" name="age"placeholder="Enter your age" class="box"<br><br>
        <label>Which option best describe your current role?</label><br><br>
    </div>
    <div id="optional">
      <select>
    <option name ="<Select Your Role">select your role</option>
     <option value ="student">student </option>
     <option value="Full Time Job">Full Time Job</option>sss
     <option value="Full Time Learner">Full Time Learner</option>
     <option value="Prefer Not To Say">Prefer Not To Say</option>
     <option value="other">other</option>
      </select>
    </div>
    <br>
    <label id="head1">Would you recommend freecodecamp to a friend?</label><br><br>
     <input type="radio" name="radio" class="larger">&nbsp&nbsp&nbspDefinitely<br><br>
     <input type="radio" name="radio" class="larger">&nbsp&nbsp&nbspMaybe<br><br>
     <input  type="radio" name="radio"class="larger">&nbsp&nbsp&nbspNot Sure<br><br>
      <label> What is your favourite feature of freecodecamp? </label><br>
      <div id="option2">
      <select>
        <option name="Select an option">Select an option </option>  
        <option value="Challenged">Challenged</option>    
        <option value="Project">Projects</option>   
        <option value="Community">Community</option>     
       <option value="Open source">Open source</option>     
      </select>
    </div>
    <br><br>
    <label id="head2">What would you like to see improved?(check all that apply)</label>
    <div id="content2">
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspFront-end Projects</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspBack-end Projects</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspData Visualisation</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspChallenges</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspOpen Source Community</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspGitter help rooms</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspVedios</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspCity Meetups</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspWiki</label><br><br>
    <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspForum</label><br><br>
   <input type="checkbox" name="checkbox" class="larger"><label>&nbsp&nbsp&nbspAdditional Courses</label><br><br>
 </div>
 <label id="head2">Any comment or suggestion?"</label1><br><br>
 <textarea placeholder="Enter Your Comment Here ..."></textarea>


</body>
</html>
