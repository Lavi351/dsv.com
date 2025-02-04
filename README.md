<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page1-DSV Workplace Culture & Inclusion Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        h2 {
            text-align: center;
            color: #666;
        }

        p {
            font-size: 18px;
            text-align: center;
        }

        .start-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            display: block;
            margin: 0 auto;
        }

        .start-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to the DSV Workplace Culture & Inclusion Survey</h1>
        <h2>Your Feedback Matters!</h2>
        <p>Thank you for taking the time to participate in this important survey. Your responses will help us foster a more inclusive and positive work environment for everyone.</p>
        <p>The survey is anonymous, and we encourage you to answer all questions truthfully. It will take approximately 10-15 minutes to complete.</p>
        <p>Please click the button below to start the survey.</p>
        
        <a href="page1.html">
            <button class="start-btn">Start Survey</button>
        </a>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 2-Employee Details - DSV Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        input[type="text"], input[type="email"], select {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border-radius: 4px;
            border: 1px solid #ccc;
            font-size: 16px;
        }

        .submit-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            width: 100%;
        }

        .submit-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Employee Details</h1>
        <p>Please provide your details before proceeding with the survey. Your responses are confidential.</p>

        <form action="survey_page_1.html" method="post"> <!-- Link to your first survey page -->

            <!-- Name -->
            <div class="form-group">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required>
            </div>

            <!-- Job Title -->
            <div class="form-group">
                <label for="job_title">Job Title</label>
                <input type="text" id="job_title" name="job_title" required>
            </div>

            <!-- Department -->
            <div class="form-group">
                <label for="department">Department</label>
                <input type="text" id="department" name="department" required>
            </div>

            <!-- Email (Optional) -->
            <div class="form-group">
                <label for="email">Email Address (Optional)</label>
                <input type="email" id="email" name="email">
            </div>

            <!-- Submit Button -->
            <button type="submit" class="submit-btn">Proceed to Survey</button>
        </form>
    </div>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page3-DSV Workplace Culture & Inclusion Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        .question {
            margin-bottom: 20px;
        }

        .options {
            display: flex;
            flex-direction: column;
        }

        .options input {
            margin-right: 10px;
        }

        .submit-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        .submit-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>DSV Workplace Culture & Inclusion Survey</h1>
        
        <form action="#" method="post">
            <!-- Question 1 -->
            <div class="question">
                <label>1. Do you feel that DSV provides an inclusive and welcoming workplace for all employees?</label>
                <div class="options">
                    <label><input type="radio" name="q1" value="Strongly agree"> Strongly agree</label>
                    <label><input type="radio" name="q1" value="Agree"> Agree</label>
                    <label><input type="radio" name="q1" value="Neutral"> Neutral</label>
                    <label><input type="radio" name="q1" value="Disagree"> Disagree</label>
                    <label><input type="radio" name="q1" value="Strongly disagree"> Strongly disagree</label>
                </div>
            </div>

            <!-- Question 2 -->
            <div class="question">
                <label>2. How often do you feel that diversity and inclusion are openly discussed at DSV?</label>
                <div class="options">
                    <label><input type="radio" name="q2" value="Frequently"> Frequently</label>
                    <label><input type="radio" name="q2" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q2" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q2" value="Never"> Never</label>
                </div>
            </div>

            <!-- Question 3 -->
            <div class="question">
                <label>3. Have you personally experienced or witnessed any form of discrimination at DSV?</label>
                <div class="options">
                    <label><input type="radio" name="q3" value="Yes, frequently"> Yes, frequently</label>
                    <label><input type="radio" name="q3" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q3" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q3" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 4 -->
            <div class="question">
                <label>4. Do you believe that employees from all backgrounds have equal access to career growth and development opportunities at DSV?</label>
                <div class="options">
                    <label><input type="radio" name="q4" value="Yes, definitely"> Yes, definitely</label>
                    <label><input type="radio" name="q4" value="Somewhat, but there are barriers"> Somewhat, but there are barriers</label>
                    <label><input type="radio" name="q4" value="No, there are noticeable inequalities"> No, there are noticeable inequalities</label>
                    <label><input type="radio" name="q4" value="Unsure"> Unsure</label>
                </div>
            </div>

            <!-- Question 5 -->
            <div class="question">
                <label>5. Do you feel comfortable expressing your identity (e.g., race, gender, religion, sexual orientation) at work without fear of bias or discrimination?</label>
                <div class="options">
                    <label><input type="radio" name="q5" value="Yes, always"> Yes, always</label>
                    <label><input type="radio" name="q5" value="Most of the time"> Most of the time</label>
                    <label><input type="radio" name="q5" value="Sometimes"> Sometimes</label>
                    <label><input type="radio" name="q5" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q5" value="No, never"> No, never</label>
                </div>
            </div>

            <button type="submit" class="submit-btn">Submit Survey</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 4-DSV Power Dynamics & Workplace Equality Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        .question {
            margin-bottom: 20px;
        }

        .options {
            display: flex;
            flex-direction: column;
        }

        .options input {
            margin-right: 10px;
        }

        .submit-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        .submit-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Power Dynamics & Workplace Equality</h1>

        <form action="thankyou.html" method="post">
            <!-- Question 6 -->
            <div class="question">
                <label>6. Do you feel that leadership at DSV actively promotes diversity and inclusion?</label>
                <div class="options">
                    <label><input type="radio" name="q6" value="Yes, strongly"> Yes, strongly</label>
                    <label><input type="radio" name="q6" value="Somewhat"> Somewhat</label>
                    <label><input type="radio" name="q6" value="Not sure"> Not sure</label>
                    <label><input type="radio" name="q6" value="No, leadership does not focus on this"> No, leadership does not focus on this</label>
                </div>
            </div>

            <!-- Question 7 -->
            <div class="question">
                <label>7. Have you ever felt that your ideas or contributions were overlooked due to bias (e.g., gender, race, seniority, etc.)?</label>
                <div class="options">
                    <label><input type="radio" name="q7" value="Yes, frequently"> Yes, frequently</label>
                    <label><input type="radio" name="q7" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q7" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q7" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 8 -->
            <div class="question">
                <label>8. Do you feel comfortable reporting concerns about discrimination or bias to HR or management?</label>
                <div class="options">
                    <label><input type="radio" name="q8" value="Yes, without hesitation"> Yes, without hesitation</label>
                    <label><input type="radio" name="q8" value="Yes, but I worry about retaliation"> Yes, but I worry about retaliation</label>
                    <label><input type="radio" name="q8" value="No, I do not trust the reporting process"> No, I do not trust the reporting process</label>
                    <label><input type="radio" name="q8" value="No, I don’t think anything would change"> No, I don’t think anything would change</label>
                </div>
            </div>

            <!-- Question 9 -->
            <div class="question">
                <label>9. Have you noticed patterns of favoritism or unequal treatment in promotions, assignments, or recognition?</label>
                <div class="options">
                    <label><input type="radio" name="q9" value="Yes, frequently"> Yes, frequently</label>
                    <label><input type="radio" name="q9" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q9" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q9" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 10 -->
            <div class="question">
                <label>10. Do you think there are any “unwritten rules” or insider networks at DSV that make it harder for some employees to advance?</label>
                <div class="options">
                    <label><input type="radio" name="q10" value="Yes, definitely"> Yes, definitely</label>
                    <label><input type="radio" name="q10" value="Somewhat"> Somewhat</label>
                    <label><input type="radio" name="q10" value="No, everyone has an equal opportunity"> No, everyone has an equal opportunity</label>
                </div>
            </div>

            <button type="submit" class="submit-btn">Submit Survey</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DSV Diversity & Representation Survey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        .question {
            margin-bottom: 20px;
        }

        .options {
            display: flex;
            flex-direction: column;
        }

        .options input {
            margin-right: 10px;
        }

        .submit-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        .submit-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Diversity & Representation</h1>

        <form action="thankyou.html" method="post">
            <!-- Question 11 -->
            <div class="question">
                <label>11. Do you feel that leadership positions at DSV reflect a diverse range of employees?</label>
                <div class="options">
                    <label><input type="radio" name="q11" value="Yes, definitely"> Yes, definitely</label>
                    <label><input type="radio" name="q11" value="Somewhat, but there is room for improvement"> Somewhat, but there is room for improvement</label>
                    <label><input type="radio" name="q11" value="No, leadership lacks diversity"> No, leadership lacks diversity</label>
                </div>
            </div>

            <!-- Question 12 -->
            <div class="question">
                <label>12. Do you believe that hiring and recruitment practices at DSV prioritize diversity and inclusion?</label>
                <div class="options">
                    <label><input type="radio" name="q12" value="Yes, always"> Yes, always</label>
                    <label><input type="radio" name="q12" value="Sometimes"> Sometimes</label>
                    <label><input type="radio" name="q12" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q12" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 13 -->
            <div class="question">
                <label>13. Have you received any formal training on diversity and inclusion at DSV?</label>
                <div class="options">
                    <label><input type="radio" name="q13" value="Yes, and it was helpful"> Yes, and it was helpful</label>
                    <label><input type="radio" name="q13" value="Yes, but it was not effective"> Yes, but it was not effective</label>
                    <label><input type="radio" name="q13" value="No, but I would like to"> No, but I would like to</label>
                    <label><input type="radio" name="q13" value="No, and I’m not interested"> No, and I’m not interested</label>
                </div>
            </div>

            <!-- Question 14 -->
            <div class="question">
                <label>14. In your experience, do employees from underrepresented backgrounds (e.g., women, visible minorities, LGBTQ+, individuals with disabilities) face additional challenges at DSV?</label>
                <div class="options">
                    <label><input type="radio" name="q14" value="Yes, frequently"> Yes, frequently</label>
                    <label><input type="radio" name="q14" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q14" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q14" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 15 -->
            <div class="question">
                <label>15. Do you believe that DSV should take more proactive steps to improve diversity and inclusion?</label>
                <div class="options">
                    <label><input type="radio" name="q15" value="Yes, definitely"> Yes, definitely</label>
                    <label><input type="radio" name="q15" value="Maybe"> Maybe</label>
                    <label><input type="radio" name="q15" value="No, it is not necessary"> No, it is not necessary</label>
                </div>
            </div>

            <button type="submit" class="submit-btn">Submit Survey</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page5-DSV Survey - Microaggressions & Workplace Behavior / Solutions & Improvement</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        .question {
            margin-bottom: 20px;
        }

        .options {
            display: flex;
            flex-direction: column;
        }

        .options input {
            margin-right: 10px;
        }

        .submit-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        .submit-btn:hover {
            background-color: #45a049;
        }

        .open-ended {
            margin-top: 10px;
            margin-bottom: 20px;
            width: 100%;
            height: 100px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Microaggressions & Workplace Behavior / Solutions & Improvement Areas</h1>

        <form action="thankyou.html" method="post">
            <!-- Question 16 -->
            <div class="question">
                <label>16. Have you experienced or witnessed microaggressions at work (e.g., subtle biased comments, stereotypes, exclusion)?</label>
                <div class="options">
                    <label><input type="radio" name="q16" value="Yes, frequently"> Yes, frequently</label>
                    <label><input type="radio" name="q16" value="Occasionally"> Occasionally</label>
                    <label><input type="radio" name="q16" value="Rarely"> Rarely</label>
                    <label><input type="radio" name="q16" value="No, never"> No, never</label>
                </div>
            </div>

            <!-- Question 17 -->
            <div class="question">
                <label>17. Do you feel comfortable addressing or reporting microaggressions when they occur?</label>
                <div class="options">
                    <label><input type="radio" name="q17" value="Yes, always"> Yes, always</label>
                    <label><input type="radio" name="q17" value="Sometimes"> Sometimes</label>
                    <label><input type="radio" name="q17" value="No, I fear backlash"> No, I fear backlash</label>
                    <label><input type="radio" name="q17" value="No, I don’t think anything would change"> No, I don’t think anything would change</label>
                </div>
            </div>

            <!-- Question 18 -->
            <div class="question">
                <label>18. What do you think are the biggest barriers to a more diverse and inclusive workplace at DSV? (Select up to 3)</label>
                <div class="options">
                    <label><input type="checkbox" name="q18" value="Lack of leadership commitment"> Lack of leadership commitment</label>
                    <label><input type="checkbox" name="q18" value="Bias in hiring and promotions"> Bias in hiring and promotions</label>
                    <label><input type="checkbox" name="q18" value="Limited training or awareness"> Limited training or awareness</label>
                    <label><input type="checkbox" name="q18" value="Fear of speaking up about issues"> Fear of speaking up about issues</label>
                    <label><input type="checkbox" name="q18" value="Workplace culture that discourages diversity"> Workplace culture that discourages diversity</label>
                    <label><input type="checkbox" name="q18" value="Other"> Other (please specify)</label>
                    <input type="text" name="q18_other" placeholder="Please specify" class="open-ended">
                </div>
            </div>

            <!-- Question 19 -->
            <div class="question">
                <label>19. What specific actions do you think DSV could take to improve diversity and inclusion? (Open-ended response)</label>
                <textarea name="q19" class="open-ended" placeholder="Your answer here"></textarea>
            </div>

            <!-- Question 20 -->
            <div class="question">
                <label>20. Would you be interested in participating in diversity and inclusion initiatives (e.g., mentorship programs, focus groups, training)?</label>
                <div class="options">
                    <label><input type="radio" name="q20" value="Yes, definitely"> Yes, definitely</label>
                    <label><input type="radio" name="q20" value="Maybe, depending on the format"> Maybe, depending on the format</label>
                    <label><input type="radio" name="q20" value="No, I’m not interested"> No, I’m not interested</label>
                </div>
            </div>

            <button type="submit" class="submit-btn">Submit Survey</button>
        </form>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 6-Thank You for Participating!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        p {
            font-size: 18px;
            text-align: center;
            color: #555;
        }

        .button {
            display: block;
            width: 200px;
            padding: 10px 0;
            margin: 30px auto;
            background-color: #4CAF50;
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 4px;
            font-size: 18px;
        }

        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Thank You for Your Participation!</h1>
        <p>Your feedback is valuable and will help us improve diversity and inclusion at DSV. We appreciate the time you’ve taken to provide your insights.</p>
        
        <a href="index.html" class="button">Return to Survey</a>  <!-- Link back to the main page, if needed -->

    </div>

</body>
</html>

