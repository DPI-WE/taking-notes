# Taking Notes 📝
In this lesson, you will learn how to effectively take notes using Markdown. Keeping well-organized notes is essential for tracking your progress, recording important information, and staying on top of tasks. This lesson will guide you through setting up a notes folder, using Markdown for note-taking, and leveraging Git for version control and sharing.

## Why Take Notes?
Keeping notes offers several benefits:

- **Clarification and Internalization**: Writing about what you’re doing helps clarify and internalize the information.
- **Documentation**: Notes serve as a record for what you work on each day, which is helpful for your future self and preparing for meetings (eg Stand-ups).
- **Reference**: When you need to perform the same task again in the future, your notes serves as a cheat sheet.
- **Professional Showcase**: Your notes serve as a greate source for your TIL blogs, which looks great to prospective employers, demonstrating both your writing and technical ability.

## Why Markdown?
[Markdown](https://www.markdownguide.org/) is a lightweight markup language that allows you to format text easily and readably. Here are some reasons why Markdown is beneficial for note-taking:

- **Simplicity**: Markdown's syntax is straightforward and easy to learn. You can format text without needing to know complex commands.
- **Readability**: Notes written in Markdown are clean and easy to read, even in plain text format.
- **Portability**: Markdown files are plain text files, which means they can be opened and edited on any device and with any text editor.
- **Compatibility**: Markdown can be converted to various formats such as HTML, PDF, and Word, making it versatile for different uses.
- **Integration**: Many tools and platforms support Markdown, including GitHub, Jupyter Notebooks, and documentation generators like MkDocs and Jekyll.

## Setting Up Your Notes Folder

### Step 1: Create a Notes Folder
Create a `notes` folder inside your `Workspace` folder. This will be the designated location for all your notes.

![](/assets/taking-notes-1.png)

### Step 2: Using Markdown for Notes
Create a New Markdown File Each Day. (`*.md`) Each morning, create a new Markdown file for your daily notes. This can include how you spend your time, meeting notes, important links, and your to-do list for the day.

### Step 3: Install Visual Studio Code
Install Visual Studio Code (VS Code). VS Code is a powerful and user-friendly code editor that is excellent for writing notes in Markdown. [Download and install VS Code](https://code.visualstudio.com/)

### Step 4: Optional - Set Up a Git Repository
Make Your Notes Folder a Git Repository. This step is optional but highly recommended. By making your notes folder a Git repository, you can version control your notes and easily share them between multiple devices. Initialize a Git repository in your notes folder and commit your changes regularly. Push commits to a GitHub repository to keep your notes backed up and accessible from anywhere.

## Example of a Daily Notes File
Here is an example of what your daily Markdown file might look like:

```markdown
<!-- Workspace/notes/2024-05-15_notes.md -->
# Notes for May 15, 2024

## Time Tracking
- 9:00 AM - 10:00 AM: Team meeting
- 10:00 AM - 12:00 PM: Coding session

## Meeting Notes
### Team Meeting
- Discussed project updates
- Assigned tasks for the week

## To-Do List
- [ ] Finish coding feature X
- [ ] Review pull requests
- [ ] Prepare for client presentation

## Important Links
- [Project documentation](https://example.com/docs)
- [Client presentation slides](https://example.com/slides)
```

# Quiz
- What is Markdown?
- A programming language.
  - Not correct. Markdown is a lightweight markup language.
- A lightweight markup language used for formatting text.
  - Correct! Markdown is used for formatting text and is easy to write and read.
- A version control system.
  - Not correct. Git is a version control system.
{: .choose_best #what_is_markdown title="What is Markdown?" points="1" answer="2"}

- Why should you use a Git repository for your notes folder?
- To make your notes look fancy.
  - Not correct. Git is used for version control and sharing.
- To version control your notes and share them between devices.
  - Correct! Git helps you keep track of changes and share notes easily.
- To write code in your notes.
  - Not correct. While you can write code snippets in Markdown, Git is primarily for version control.
{: .choose_best #git_repository title="Why Use a Git Repository?" points="1" answer="2"}

- Visual Studio Code is a suitable tool for writing notes in Markdown.
- True
  - Correct! Visual Studio Code is a powerful editor that supports Markdown.
- False
  - Not correct. Visual Studio Code is indeed suitable for writing Markdown notes.
{: .choose_best #vscode_suitable title="Is Visual Studio Code Suitable for Markdown?" points="1" answer="1"}

<!-- Possible answers: Tracking progress, recording important information, staying organized, creating a reference for future use. -->
- Name one benefit of keeping a daily notes file.
{: .free_text #daily_notes_benefit title="Benefit of Keeping Daily Notes" points="1"}

- Have you created a notes folder and a markdown file for today's notes?
- Yes
  - Great! Remember to create a new markdown file each day for your notes.
- No
  - Please create a notes folder and markdown file for today's notes before continuing.
{: .choose_best #notes_folder title="Have you created a notes folder?" points="1" answer="1"}
