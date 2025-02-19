# FitLife - virtual sports coaching platform



The FitLife project aims to create a web application where users can receive virtual sports coaching platform. This platform provides personalized guidance and support to help users achieve their fitness and healthy lifestyle goals.

## Introduction

The FitLife project is a web application designed to offer virtual sports coaching platform. It aims to assist users in achieving their fitness goals by providing personalized workout programs, nutrition plans, and direct communication with experienced trainers.

## Technologies Used

- **Programming Languages:** Java Spring, Mern stack
- **Database:** Cloud-based relational database service
- **Web Development:** HTML, CSS, JavaScript

## Project Overview

The FitLife platform comprises several key features:

1. **User Registration and Login:**
   - Users can register by providing basic personal information such as name, surname, date of birth, gender, email address, phone number, and profile photo.
   - Users can log in using their email and securely stored password. Authentication processes should be implemented.
   - A "forgot password" option is available for users to reset their passwords.

2. **User Profiles:**
   - Users can edit their personal profile pages, add profile pictures, and update basic information.

3. **User Roles:**
   - The application has three user roles: Admin, Trainer, and Trainee.
   - Admins have comprehensive access rights for general application management, including managing user accounts and data.
   - Trainers can edit their profile information, access information about assigned trainees, create and update exercise programs, and create and update nutrition plans.
   - Trainees can view and edit their profiles, access exercise and nutrition plans, communicate with trainers, add and manage progress records, and view visual reports.

4. **Trainer Profiles:**
   - Trainers can edit their profile information, including name, surname, specialization areas (weight gain, weight loss, weight maintenance, muscle gain), experiences, and contact details.

5. **Trainer-Trainee Relationship:**
   - After trainees enter their personal information and goals, the system will systematically match trainers based on their expertise and the number of trainees they can handle.
   - Each trainer can have a maximum of 5 trainees.

6. **Database Design:**
   - Utilize a cloud-based relational database service
   - Design tables such as 'User,' 'Trainer,' 'Workout Programs,' 'Nutrition Plans,' 'Messaging,' and 'User-Trainer Relationship.'
   - Establish relationships between tables using keys, ensuring normalization.



## Usage

1. **Installation:**
   - Clone the repository: 
     ```
     git clone https://github.com/your-username/fitlife.git
     ```
   - Navigate to the project directory:
     ```
     cd fitlife
     ```

2. **Running the Application:**
   - Start the application using your preferred web development environment.

3. **Accessing the Interface:**
   - The application should provide a user-friendly web interface for users, trainers, and admins.

## Important Notes

- Visualize the dynamic aspects of the program, such as progress reports and interactive communication.
- Regularly update the documentation to reflect any changes or improvements in the project.


