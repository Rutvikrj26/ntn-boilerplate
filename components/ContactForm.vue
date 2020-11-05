<template>

  <form action="action_page.php">
<ul>    
<li>  <label for="fname"><h3>First Name</h3></label>
    <input type="text" 
  id="fname" name="firstname" placeholder="Your name..">
    
    <label for="lname"><h3>Last Name</h3></label>
    <input type="text" 
  id="lname" name="lastname" placeholder="Your last name.."></li>
    
<li>  <label for="email"><h3>Email</h3></label>
    <input type="email" 
  id="email" name="Email-Id" placeholder="Your Email- ID"></li>
    
<li>  <label for="subject"><h3>Subject</h3></label>
    <textarea 
  id="subject" name="subject" placeholder="Write something.." 
  style="height:200px width:400"></textarea></li>

<li>    <input 
  type="submit" value="Submit"></li>
</ul>

  </form>

</template>
