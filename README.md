# CS2-JASMINE_Cortez-Avestruz-project
#Title: ISKALARSync

ISKALARSync is a command-line based task management program designed to help students organize and prioritize their academic workload. The system allows users to create tasks, assign them to specific subjects, set difficulty levels, and input due dates.

The program automatically prioritizes tasks based on urgency (due date) and complexity (difficulty level), helping users focus on the most important tasks first. Additionally, it tracks completed tasks and provides motivational feedback to encourage productivity.

Features
- Task creation with subject, difficulty, and due date
- Automatic task prioritization (due date and difficulty)
- Due date tracking with overdue detection
- Task completion and storage of finished tasks
- Input validation and error handling
- Motivational feedback system

System Requirements
- Python 3.x installed on the computer
- A terminal or command-line interface (Command Prompt, Terminal, etc.)

1. Ensure that Python 3 is installed on your system.
2. Save the program file (e.g., iskalarsync.py).
3. Open a terminal or command prompt.
4. Navigate to the folder where the file is located.
5. Run the program using the command:
   python iskalarsync.py

How to Use:
After running the program, the user is presented with a menu containing four options:

1. Add new task
2. View all tasks (prioritized)
3. Mark a task done
4. Exit

Adding Tasks
- Input the task name, subject, difficulty (1–10), and due date (YYYY-MM-DD).
- The program validates inputs and warns if the task is already overdue.
Viewing Tasks
- Displays all tasks sorted by earliest due date and highest difficulty.
- Shows remaining days or marks tasks as overdue.
Completing Tasks
- Select a task from the list to mark it as done.
- Completed tasks are stored and removed from the active list.
- A random motivational message is displayed.
Exiting
- Users may choose to view completed tasks before exiting the program.

Program Structure
- Lists are used to store tasks, finished tasks, subjects, and motivational messages
- Dictionaries store individual task details (name, subject, difficulty, due date)
- Functions handle input validation and date checking
- Sorting with lambda functions is used for prioritizing tasks
- datetime module is used for handling dates
- random module is used for generating motivational messages

Limitations
- Data is not saved permanently (all tasks reset when the program is closed)
- Limited storage system (tasks are only stored during runtime using lists)
- Basic prioritization (only considers due date and difficulty, not other factors like subject weight or time needed)
- Limited input flexibility (strict date format and numeric inputs required)
- GUI features may be basic and lack advanced interface elements (e.g., drag-and-drop, calendar integration, notifications)
