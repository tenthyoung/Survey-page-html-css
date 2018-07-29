<body class="bg">
<form id="survey-form">
  <h1 id="title">Survey Form</h1>
  <fieldset>
    <p id="description">Sign up for StudyRPG. </p>
    <label id="name-label">Name: 
      <input type="text" id="name" placeholder="Enter First & Last Name"> </input>
    </label><br>
    <label id="email-label">Email: 
      <input type="email" id="email" placeholder="Enter Email"> </input>
    </label><br>
    <label id="number-label"> Age: 
      <input type="number" min="1" max="150" id="number" placeholder="Enter Age"> </input>
    </label><br>
    <label id="dropdown"> What is your current role?
      <select>
        <option value="Middle School Student">Middle School Student</option>
        <option value="High School Student">High School Student</option>
        <option value="College Student">College Student</option>
        <option value="Teacher">Teacher</option>
        <option value="Self-learner">Self-Learner</option>
      </select>
    </label> <br>
    <label id="gender"> What is your gender?</label>
    </div>
      <div class="rightTab">
        <ul style="list-style: none;">
          <li class="radio"><label><input name="radio-buttons" value="1"  type="radio" class="userRatings" ></label>Female</li>
          <li class="radio"><label><input name="radio-buttons" value="2"  type="radio" class="userRatings" ></label>Male</li>
          <li class="radio"><label><input name="radio-buttons" value="3"  type="radio" class="userRatings" ></label>Other</li>
        </ul>
      </div>
    </div>
    <div class="rowTab">
      <div class="labels">
        <label for="preferences">What classes are you interested in?<br>(Check all that apply): </label>
      </div>
      <div class="rightTab">
        <ul id="preferences" style="list-style: none;">
          <li class="checkbox"><label><input name="prefer" value="1" type="checkbox" class="userRatings">Warrior</label></li>
          <li class="checkbox"><input name="prefer" value="2" type="checkbox" class="userRatings">Thief</li>
          <li class="checkbox"><label><input name="prefer" value="3" type="checkbox" class="userRatings">Mage</label></li>
          <li class="checkbox"><label><input name="prefer" value="4" type="checkbox" class="userRatings">Healer</label></li>
          <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Knight</label></li>
          <li class="checkbox"><label><input name="prefer" value="6" type="checkbox" class="userRatings">Samurai</label></li>
          <li class="checkbox"><label><input name="prefer" value="7" type="checkbox" class="userRatings">Ninja</label></li>
          <li class="checkbox"><label><input name="prefer" value="8" type="checkbox" class="userRatings">Scout</label></li>
          <li class="checkbox"><label><input name="prefer" value="9" type="checkbox" class="userRatings">Alchemist</label></li>
          <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Summoner</label></li>
          <li class="checkbox"><label><input name="prefer" value="10" type="checkbox" class="userRatings">Necromancer</label></li>
        </ul>
      </div>
    </div>
    <div class="rowTab">
      <div class="labels">
        <label for="comments">Any Comments or Suggestions?</label>
      </div>
      <div class="rightTab">
        <textarea id="comments" class="input-field" style="height:150px;width:500px;resize:vertical;" name="comment" placeholder="Enter your comment here..."></textarea>
      </div>
    </div>
    <button id="submit" type="submit">Submit</button>
  </form>
</div>
  </fieldset>
</form>
</body>


//CSS portion
@import url(https://fonts.googleapis.com/css?family=Raleway:400,500);

.bg {
  background-image: url("https://www.palaiszelda.com/cado/fds-ecran/botw_1_1920.jpg");
  height: 100%;
  background-position: 0px -60px;
  background-repeat: no-repeat;
  background-size: auto;
}

#title {
  color: #C4A42F;
  font-weight: bold;
}

body {
  height: 100%;
  margin: 0;
  font-family: 'Raleway', Helvetica, sans-serif, Times New Roman;
  text-align: center;
}


fieldset {
  background-color: white;
  margin: auto;
  width: 650px;
  font-size: 150%;
}



li.radio {
  font-size: 20px;
}

@media (min-width: 500px){
  fieldset {
    width: 0%;
  }
}

@media (min-width: 501px){
  fieldset {
    width: 40%;
  }
}
