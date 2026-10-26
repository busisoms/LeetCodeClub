# LeetCode Club

A collaborative space to learn Data Structures & Algorithms (DSA) through LeetCode challenges, code reviews, and shared problem-solving.

## Our Goal

To understand algorithms, improve our problem-solving skills, and learn from each other's approaches.

We're not competing to find the fastest solution. We're here to learn together.

## How We Work

### 1. Clone the Repository

```
git clone <repository-url>
cd leetcode-club
```

### 2. Create Your Branch

Before starting a problem, make sure your local `main` branch is up to date:

```
git checkout main
git pull origin main
git checkout -b yourname/problem-name
```

Example:

```
git checkout -b busiso/two-sum
```

### 3. Solve the Problem

Put your solution in your own folder inside the problem's folder. If the problem folder doesn't exist yet, create it. If it does, just add your folder inside it.

```
leetcode-club/
├── README.md
└── problems/
    └── two-sum/
        ├── busiso/
        │   └── Solution.java
        └── contributor2/
            └── Solution.java
```

Because everyone works in their own folder, multiple people can submit different solutions to the same problem without conflicts.

### 4. Push Your Solution

Once you're happy with your solution, add only your own folder:

```
git add problems/two-sum/yourname
git commit -m "Add two-sum solution (yourname)"
git push -u origin yourname/problem-name
```

### 5. Open a Pull Request (PR)

On GitHub, open a Pull Request targeting `main`. In the description, briefly explain:

- **Understanding:** What is the problem asking?
- **Approach:** How did you solve it?
- **Complexity:** What are the time and space complexities?
- **Challenges (optional):** What did you struggle with?

Don't worry about having the most optimised solution. We want to understand your thought process.

### 6. Review Together

During our meetings, we'll:

1. Go through each other's PRs.
2. Explain our solutions.
3. Discuss different approaches and possible improvements.
4. Approve solutions that are correct and understood.

Once approved, the PR can be merged into `main`.

## Club Rules

- Don't push directly to `main`.
- Always create a branch and open a PR.
- Review each other's code respectfully.
- Different correct approaches are welcome.
- Ask questions when something isn't clear.
- Focus on understanding, not just getting an accepted solution.

## After Your PR Is Merged

Before starting another problem, update your local repository:

```
git checkout main
git pull origin main
```

Then create a new branch for the next problem.

## Remember

The goal isn't just to solve problems. It's to understand why our solutions work and to help each other become better problem solvers.

Happy coding!
