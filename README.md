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
            <label>What is your favorite feature of freeCodeCamp?<input /></label>
            </fieldset>
        </form>
      </body>
      </html> 