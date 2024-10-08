<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grand Opening - PowerCore Gym</title>
    <style>
        body {
            background-color: #8fbc8f; /* Dark Sea Green for a calming background */
            color: #733924; /* Dark Mahogany for text */
            font-family: 'Verdana', sans-serif;
            padding: 20px;
            line-height: 1.6;
        }

        .header {
            background-color: #dbffdb; /* Light Green background for header */
            padding: 30px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        h1 {
            font-size: 2.8em;
            color: #4a6f4a; /* Deep Green for title text */
            margin: 0;
        }

        h2 {
            font-size: 1.8em;
            color: #4a6f4a; /* Deep Green for subtitle */
            margin: 10px 0;
        }

        .container {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
        }

        .content-block {
            background-color: skyblue; /* Sky Blue for content blocks */
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex: 1;
            min-width: 280px;
            color: #733924; /* Dark Mahogany for text */
        }

        .content-block p {
            font-size: 1.1em;
        }

        .beliefs {
            background-color: #bc8fa5; /* Soft Pink for belief statements */
            padding: 15px;
            margin: 10px 0;
            text-align: center;
            border-radius: 10px;
            color: white;
            font-size: 1.2em;
        }

        .logo-container {
            text-align: center;
            margin-top: 20px;
        }

        img {
            border-radius: 50%;
            width: 130px;
            height: 130px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Form Styling */
        .registration-form {
            background-color: skyblue;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }

        .registration-form h2 {
            color: #bc8fa5; /* Matching form header color */
            font-size: 1.8em;
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-size: 1.2em;
        }

        input[type="text"], input[type="email"], select {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            border: 2px solid #bc8fa5;
            border-radius: 5px;
            font-size: 1em;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #bc8fa5;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        input[type="submit"]:hover {
            background-color: #9f7185;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .content-block {
                margin-bottom: 20px;
            }

            h1 {
                font-size: 2.4em;
            }

            h2 {
                font-size: 1.6em;
            }

            input[type="submit"] {
                font-size: 1.1em;
            }
        }
    </style>
</head>

<body>

    <div class="header">
        <h1>GRAND OPENING!</h1>
        <h2>Start Your Fitness Journey</h2>
    </div>

    <div class="container">
        <div class="content-block">
            <p>We are thrilled to announce the grand opening of PowerCore Gym on October 16, 2024! Join us at 1:00 PM for an exciting day filled with fitness, fun, and community. Our state-of-the-art facilities will be open for you to explore, and we’ll have exclusive membership deals available for those who sign up on the opening day.</p>
        </div>

        <div class="content-block">
            <p>At PowerCore Gym, we are committed to helping our members achieve their fitness goals in a supportive and inclusive environment. Our grand opening event will feature live demonstrations of our equipment and classes, giving you a taste of what you can expect as a member. Don't miss out on the chance to win exciting prizes throughout the day, including free personal training sessions and gym merchandise!</p>
        </div>
    </div>

    <div class="container">
        <div class="beliefs">
            <p>We believe you should look and feel healthy!</p>
        </div>
        <div class="beliefs">
            <p>We believe your quality of life is enhanced by healthy workouts!</p>
        </div>
        <div class="beliefs">
            <p>We believe a healthy workout leads to a healthy heart!</p>
        </div>
    </div>

    <div class="logo-container">
        <img src="PowerCore Gym Logo.jpg" alt="PowerCore Gym Logo">
    </div>

    <!-- Registration Form -->
    <div class="registration-form">
        <h2>Register for the Grand Opening Event</h2>
        <form action="your_form_submission_url" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required>

            <label for="class">Select a Fitness Class:</label>
            <select id="class" name="class">
                <option value="yoga">Yoga</option>
                <option value="strength_training">Strength Training</option>
                <option value="cardio">Cardio</option>
                <option value="spin">Spin Class</option>
            </select>

            <input type="submit" value="Register">
        </form>
    </div>

</body>

</html>
