# TasksBackStackLaunchModesTutorial

This project demonstrates Android activity navigation using tasks, back stack, and different launch modes (`standard`, `singleTop`, `singleTask`, `singleInstance`). It shows how activities are managed within the back stack and tasks for efficient navigation and task handling.

## Concepts
- **Back Stack**: Android maintains a back stack that represents the history of activities. When navigating between activities, the system pushes and pops activities from this stack.
- **Tasks**: A task is a collection of activities that are logically connected, and the task stack is used to manage navigation between these activities.
- **Launch Modes**: The four main launch modes in Android control how new activities are instantiated and added to the back stack:
  - `standard`: A new instance of the activity is created every time.
  - `singleTop`: If the activity is already on top of the stack, it will be reused instead of creating a new instance.
  - `singleTask`: The activity is always placed in its own task, and if an instance already exists, it will be reused.
  - `singleInstance`: The activity is placed in its own task, and no other activity can be added to that task.

## Features
- Demonstrates activity navigation with different launch modes.
- Handles activity tasks and back stack operations.
- Provides examples for using `standard`, `singleTop`, `singleTask`, and `singleInstance` launch modes.

## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/tashafdev/TasksBackStackLaunchModesTutorial.git
    ```

2. Open the project in Android Studio.

3. Run the app on a physical device or emulator.

## Usage
- Navigate between activities using different launch modes.
- Observe how the back stack and tasks are managed for each launch mode.

## Contributing
Feel free to fork the repository and submit pull requests for enhancements or bug fixes.
