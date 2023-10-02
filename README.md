# Surveyform
<!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Survey Form</title>
      <link rel="stylesheet" href="styles.css" />
      </head>
      <body>
      <h1 id="title">freeCodeCamp Survey Form</h1>
      <p id="description"><em>Thank you for taking the time to help us improve the platform</em></p>
      <form method="post" action="https://survey-form.freecodecamp.rocks/">
      <fieldset>
        <label for="name">Name<input name="name" id="name" type="text" placeholder="Enter your name" required/></label>
        <label for="email:">Email<input name="email" id="email" type="email" placeholder="Enter your Email" required/></label>
        <label for="age">Age (optional)<input name="age" id="age" type="number" placeholder="age" required/></label>
        </fieldset>
        <label for="current-role">Which option best describes your current role?<select>
          <option value="">Select current role</option>
          <option value="1">Student</option>
          <option value="2">Full Time Job</option>
          <option value="3">Full Time Learner</option>
          <option value="4">Prefer not to say</option>
          <option value="5">Other</option>
          </select>
          </label>
        </fieldset>
        <fieldset>
          <label>Would you recommend freeCodeCamp to a friend?</label>
            <label for="Definitely"><input id="Definitely" checked type="radio" class="inline" name="Definitely-Maybe-Not sure"/>Definitely</label>
          <label for="Maybe"><input id="Maybe"type="radio" class="inline" name="Definitely-Maybe-Not sure"/>Maybe</label>
          <label for="Not sure"><input id="Not sure" type="radio"class="inline" name="Definitely-Maybe-Not sure"/>Not sure<label>
          </fieldset>
          <fieldset>
            <label>What is your favorite feature of freeCodeCamp?<select>
            <option value="">Select an option</option>
            <option value="1">Challenges</option>
            <option value="2">Projects</option>
            <option value="3">Community</option>
            <option value="4">Open Source</option>
            </select>
            </label>
 </fieldset>
 <fieldset>           <label>What would you like to see improved? (check all that apply)</label>
            <label for="Front-end"><input id="Front-end" type="checkbox" name="Front-end" class="inline">Front-end Projects</label>
            <label for="back-end"><input id="Back-end" name="Back-end" type="checkbox" class="inline">Back-end Projects</label>
            <label for="Data"><input id="Data" name="Data" type="checkbox" class="inline">Data Visualization</label>
            <label for="Challenges"><input id="Challenges" name="Challenges" type="checkbox" class="inline">Challenges</label>
            <label for="Open-Sourse"><input id="Open-Sourse" name="Open-Source"type="checkbox" class="inline">Open Source Community</label>
            <label for="Gitter"><input id="Gitter" name="Gitter" type="checkbox" class="inline">Gitter help rooms</label>
            <label for="Videos"><input id="Videos" name="Videos" type="checkbox" class="inline">Videos</label>
            <label for="City-Meetups"><input id="City-Meetups" name="City-Meetups" type="checkbox" class="inline">City Meetups</label>
            <label for="Wiki"><input id="Wiki" name="Wiki" type="checkbox" class="inline">Wiki</label>
            <label for="Forum"><input id="Forum" name="Forum" type="checkbox" class="inline">Forum</label>
            <label for="Courses"><input id="Courses" name="Courses" type="checkbox" class="inline" />Additional Courses</label>
            </fieldset>
        </form>
      </body>
      </html>