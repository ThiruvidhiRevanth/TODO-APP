#Todo App
This is a simple Todo app built using FlutterFlow and Supabase. The app allows users to add, update, and delete tasks, which are stored in a Supabase backend.

#Features
Add new tasks
Mark tasks as completed
Edit existing tasks
Delete tasks
Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

#Prerequisites
FlutterFlow account
Supabase account
Git installed on your local machine
Setup Supabase
Create a new project in Supabase:

Go to Supabase.
Click on "New Project".
Fill in the details and create the project.
Create a new table:

Navigate to the "Table Editor" in your Supabase project.
Create a table named todos with the following columns:
id: uuid, Primary Key, Default Value: uuid_generate_v4()
title: text
is_complete: boolean, Default Value: false
created_at: timestamp, Default Value: now()
Get your API keys:

Go to the "Settings" tab in your Supabase project.
Navigate to "API" and copy the anon key and the URL.
Setup FlutterFlow
Create a new project in FlutterFlow:

Go to FlutterFlow.
Click on "New Project" and follow the prompts to set up your project.
Connect to Supabase:

In your FlutterFlow project, go to the "Settings" tab.
Navigate to "Integrations" and select "Supabase".
Enter the anon key and the URL from your Supabase project.
Build your UI:

Use the FlutterFlow UI builder to create the interface for your Todo app.
Add components such as TextFields for task input, Buttons for adding tasks, and a ListView to display tasks.
Set up API calls:

In FlutterFlow, go to the "API Calls" section.
Create API calls to interact with your Supabase todos table (e.g., GET, POST, PUT, DELETE requests).
Deploy and Test:

Deploy your app to test it.
Contributing
Feel free to fork this repository and contribute by submitting a pull request. Any contributions are greatly appreciated!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
FlutterFlow
Supabase
