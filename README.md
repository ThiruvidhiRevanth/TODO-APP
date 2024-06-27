# Todo App

This is a simple Todo app built using [FlutterFlow](https://flutterflow.io/) and [Supabase](https://supabase.io/). The app allows users to add, update, and delete tasks, which are stored in a Supabase backend.

## Features

- Add new tasks
- Mark tasks as completed
- Edit existing tasks
- Delete tasks

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- [FlutterFlow](https://flutterflow.io/) account
- [Supabase](https://supabase.io/) account
- Git installed on your local machine

### Setup Supabase

1. **Create a new project in Supabase**:
   - Go to [Supabase](https://supabase.io/).
   - Click on "New Project".
   - Fill in the details and create the project.

2. **Create a new table**:
   - Navigate to the "Table Editor" in your Supabase project.
   - Create a table named `todos` with the following columns:
     - `id`: `uuid`, Primary Key, Default Value: `uuid_generate_v4()`
     - `title`: `text`
     - `is_complete`: `boolean`, Default Value: `false`
     - `created_at`: `timestamp`, Default Value: `now()`

3. **Get your API keys**:
   - Go to the "Settings" tab in your Supabase project.
   - Navigate to "API" and copy the `anon key` and the `URL`.

### Setup FlutterFlow

1. **Create a new project in FlutterFlow**:
   - Go to [FlutterFlow](https://flutterflow.io/).
   - Click on "New Project" and follow the prompts to set up your project.

2. **Connect to Supabase**:
   - In your FlutterFlow project, go to the "Settings" tab.
   - Navigate to "Integrations" and select "Supabase".
   - Enter the `anon key` and the `URL` from your Supabase project.

3. **Build your UI**:
   - Use the FlutterFlow UI builder to create the interface for your Todo app.
   - Add components such as TextFields for task input, Buttons for adding tasks, and a ListView to display tasks.

4. **Set up API calls**:
   - In FlutterFlow, go to the "API Calls" section.
   - Create API calls to interact with your Supabase `todos` table (e.g., GET, POST, PUT, DELETE requests).

5. **Deploy and Test**:
   - Deploy your app to test it.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. Any contributions are greatly appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [FlutterFlow](https://flutterflow.io/)
- [Supabase](https://supabase.io/)
