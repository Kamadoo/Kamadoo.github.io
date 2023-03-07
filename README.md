# Kamadoo.github.io
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Survey Form</title>
</head>
<body>
    <div class="top">
        <header class="header">
            <h1 id="title" class="center">Survey Form</h1>
            <p id="description" class="description-center">
                We are glad to hear from you. Please fill out the form below to help us improve the platform.
            </p>
        </header>
    <form id="survey-form">
        <div class="form-group">
            <label name="name-label" for="name">Name</label>
            <input type="text" name="name" id="name" class="form-control" placeholder="Enter your name" required>
        </div>
        <div class="form-group">
            <label name="email-label" for="email">Email</label>
            <input type="email" name="email" id="email" class="form-control" placeholder="Enter your Email" required>
        </div>
        <div class="form-group">
            <label name="date-label" for="date">Birthday</label>
            <input type="date" name="age" id="date" class="form-control" placeholder="Birthday">
        </div>
        <div class="form-group">
            <p>What role do you occupy right now?</p>
            <select id="dropdown" name="role" class="form-control" required>
                <option disabled selected value>Select your current role</option>
                <option value="student">Student</option>
                <option value="job">Full Time Job</option>
                <option value="other">Other</option>
            </select>
        </div>
     
        <div class="form-group">
            <p>Would you recommend our company?</p>
            <label>
                <input name="user-recommend" value="sure" type="radio" class="input-radio" checked>
                For sure!
            </label>
            <label>
                <input name="user-recommend" value="maybe" type="radio" class="input-radio">
                Maybe
            </label>
            <label>
                <input name="user-recommend" value="not-sure" type="radio" class="input-radio">
                Not sure :(
            </label>
        </div>
        <div class="form-group">
            <p>What do you think is the best thing on our company?</p>
            <select id="most-like" name="most-like" class="form-control" required>
                <option disabled selected value>Select an option</option>
                <option value="design">Design</option>
                <option value="quality">Quality</option>
                <option value="price">Price</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div class="form-group">
            <p>What do you think should be improved on our company? <span class="clue">(Check all that apply)</span></p>
            <label>
                <input name="prefer" value="design" type="checkbox" class="input-checkbox">
                Design
            </label>
            <label>
                <input name="prefer" value="quality" type="checkbox" class="input-checkbox">
                Quality
            </label>
            <label>
                <input name="prefer" value="price" type="checkbox" class="input-checkbox">
                Price
            </label>
            <label>
                <input name="prefer" value="other" type="checkbox" class="input-checkbox">
                Other: 
                <input type="text" name="other" class="form-control2">
            </label>
        </div>
        <div class="form-group">
            <p>Any other comments or suggestions?</p>
            <textarea name="comments" id="comments" class="input-textarea" placeholder="Enter your comment here..."></textarea>
        </div>
        <div class="form-group">
            <button type="submit" id="submit" class="submit-button">Submit</button>
        </div>
    </form>
  </div> 
</body>
</html>
