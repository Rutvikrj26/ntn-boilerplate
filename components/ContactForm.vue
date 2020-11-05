<template>

  <form action="action_page.php">
<ul>    
<li>  <h2><label for="fname">First Name</label></h2>
    <input type="text" 
  id="fname" name="firstname" placeholder="Your name..">
    
    <h2><label for="lname">Last Name</label></h2>
    <input type="text" 
  id="lname" name="lastname" placeholder="Your last name.."></li>
    
<li><h2><label for="email">Email</label></h2>
    <input type="email" 
  id="email" name="Email-Id" placeholder="Your Email- ID"></li>
    
<li>  <h2><label for="subject">Subject</label></h2>
    <textarea 
  id="subject" name="subject" placeholder="Your Enquiry.." 
  style="height:200px width:800px"></textarea></li>

<li><h2><input 
  type="button" value="Submit"></h2></li>
</ul>

</form>

</template>
