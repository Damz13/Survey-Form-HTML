# Survey-Form-HTML
Survey Form Practice using HTML
<script>  https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js </script> 
<html>
  <head>
  <h1 id="title"> Survey </h1>
  <p id="description"> Favorite Pet </p>
  </head>
  <main>
 <form id="survey-form"> 
   <div id="name">
     <label id="name-label"> Name </label>
   <input type="name" placeholder="Enter your name" required/>
   </div>
   <div id="email">
     <label id="email-label">Email</label>
   <input type="email" name="email" class="form-control" placeholder="Enter your email" required/>
   </div>
   <div id"number">
     <label id="number-label"> Phone Number </label>
   <input placeholder="Enter your phone number" class="form-control" type="phone-number" min="000-000-0000" max="999-999-9999" required/>
   </div>
   <select id="dropdown">
     <option value="">Please select an option</option>
     <option value="dog">Dog</option>
     <option value="cat">Cat</option>
   </select>
   <textarea placeholder="Additonal Comments">Additonal Comments</textarea> 
   <button id="submit">Submit </button>
     </form>
   </main>
  
</html>
