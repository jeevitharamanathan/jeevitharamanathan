- 👋 Hi, I’m @jeevitharamanathan
-def todo_list():
    tasks = []
    while True:
        print("\nTo-Do List:")
        for i, task in enumerate(tasks):
            print(f"{i + 1}. {task}")
        print("\nOptions:")
        print("1. Add task")
        print("2. Remove task")
        print("3. Quit")
        choice = input("Enter your choice: ")
        if choice == "1":
            task = input("Enter task: ")
            tasks.append(task)
        elif choice == "2":
            try:
                index = int(input("Enter task number to remove: ")) - 1
                del tasks[index]
            except (ValueError, IndexError):
                print("Invalid task number.")
        elif choice == "3":
            break
        else:
            print("Invalid choice.")

todo_list() 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jeevitharamanathan/jeevitharamanathan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
