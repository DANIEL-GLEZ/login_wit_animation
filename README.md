🔐 Animated Login UI with Rive 🐻

A Flutter login interface developed with an interactive Rive animation.

📄 Project Description

login_bear_animation is a Flutter demo application that showcases a dynamic login screen. Its core functionality is the integration of a Rive bear (or character) animation that reacts to user input in real-time, making the authentication process a fun and captivating experience.

⚙️ Key Features

    📧 The animated character observes the typing process (isChecking set to true) as the user completes the email field.

    🙈 When entering the password, the bear executes the "hands up" animation (controlled by the isHandsUp variable) to simulate privacy.

    ✅ Once the Login button is validated, a success animation (trigSuccess) is triggered if the entered credentials are correct and meet the validation criteria.

    ❌ If the validation fails or the credentials are incorrect, a failure animation (trigFail) is activated to indicate the error to the user.
💡 What is Rive and the State Machine?

Rive is a robust tool for developing high-quality, interactive vector animations that are synchronized with the application's logic and run in real-time. It allows the application's code to directly control the animation flow.

A State Machine is Rive's central component. It is a logical system that manages the transitions between different animation sequences based on the inputs it receives (such as SMIBool or SMITrigger) from the Flutter code.

In this project, the state machine named "Login Machine" is responsible for orchestrating all the character's reactions throughout the login interaction.
  
