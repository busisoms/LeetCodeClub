# LeetCode Club

A collaborative space to learn Data Structures and Algorithms (DSA) through LeetCode challenges, code reviews, and shared problem-solving.

## Our Goal

To understand algorithms, improve our problem-solving skills, and learn from each other's approaches.

We're not competing to find the fastest solution. We're here to learn together.

## How We Learn

We study one algorithm or problem-solving technique at a time, progressing from introductory problems to more challenging variations.

Our focus is on learning how to derive solutions independently, rather than memorising code or collecting accepted submissions.

Each topic has its own folder containing a learning guide, a problem list, and our solutions. The learning and contribution process described below applies to every topic.

## How We Approach a Problem

We follow the same problem-solving process regardless of the technique or difficulty.

### 1. Understand the Problem

Before writing code, make sure you understand what the problem is asking.

- Restate the problem in your own words.
- Identify the inputs and expected output.
- Work through the examples manually.
- Identify the constraints, including input size and value ranges.
- Consider edge cases and clarify anything that is unclear.

**Checkpoint:** Can you explain what the problem is asking without repeating the statement word for word?

### 2. Work Through a Small Example

Use a simple example to understand how the input should produce the output.

- Trace what happens step by step.
- Write down intermediate results where helpful.
- Try an example that is not provided in the problem statement.
- Consider what happens with empty, minimal, duplicate, or unusual inputs where applicable.

**Checkpoint:** Can you solve a small example by hand and explain why the answer is correct?

### 3. Develop a Solution Before Coding

Try to derive an approach before worrying about Java syntax.

- Start with the simplest solution you can think of, even if it is inefficient.
- Identify what makes that solution slow or unnecessarily complicated.
- Look for patterns or repeated work that could be avoided.
- Consider which data structures or algorithms might help.
- Write the logic as steps or pseudocode.

If you get stuck, keep experimenting with examples before seeking help. Use hints to guide your thinking without immediately jumping to a complete solution.

**Checkpoint:** Can you explain the logic of your approach without relying on code?

### 4. Consider Correctness and Complexity

Before implementing, ask yourself:

- Why should this approach work for every valid input?
- What assumptions am I making?
- Which edge cases could break it?
- How much time will it take as the input grows?
- How much additional memory will it use?

We do not need to find the optimal solution immediately. We do need to understand the trade-offs of the solution we choose.

**Checkpoint:** Can you justify why your approach works and estimate its time and space complexity?

### 5. Implement the Solution in Java

Translate your approach into readable Java code.

- Use clear variable and method names.
- Keep the implementation as simple as possible.
- Choose appropriate Java data structures.
- Avoid adding unnecessary complexity before the basic solution works.

If your implementation fails, use the error or failing test case to identify what went wrong rather than immediately replacing your solution with someone else's.

### 6. Test and Debug

Submit your solution to LeetCode and check the result.

Test more than just the example provided in the problem statement. Consider edge cases, boundary values, and inputs that challenge your assumptions.

If the solution fails:

1. Read the error message or identify the failing test case.
2. Trace your code using that input.
3. Compare the actual behaviour with the expected behaviour.
4. Identify the underlying mistake.
5. Fix the mistake and test again.

An accepted submission is a correctness checkpoint, not proof that the solution is optimal or fully understood.

### 7. Review and Improve

Once your solution works, revisit the problem.

- Does the solution handle all valid inputs?
- Is there a simpler or more efficient approach?
- Could a different data structure help?
- What are the actual time and space complexities?
- What did you learn that might help with a different problem?

Do not optimise blindly. Make sure you understand the current solution before trying to improve it.

### 8. Explain What You Learned

Before submitting your solution to the repository, make sure you can explain:

- What the problem was asking.
- How you approached it and why.
- Why your solution works.
- Its time and space complexity.
- What challenged you and how you overcame it.
- What you would consider if solving a similar problem again.

The goal is to develop independent problem-solving ability, not just produce working code.

## How We Practise Together

We use two types of practice.

### Individual Practice: Introductory Problems

For easier problems, each person attempts the problem independently and submits their own solution.

The purpose is to build familiarity with the technique and strengthen the fundamentals before tackling harder variations.

### Group Challenges: Medium and Hard Problems

For shared challenges, each person first attempts the problem independently.

- Spend approximately 30–45 minutes making a genuine attempt before discussing the solution.
- Record your approach and where you got stuck.
- During meetings, compare approaches and explain your reasoning.
- Discuss edge cases, correctness, complexity, and alternative solutions.
- Use hints when needed, but make sure you understand the final approach.

The time limit is a guideline, not a competition. The goal is to make a serious attempt before learning from the group.

## How We Work With GitHub

### 1. Clone the Repository

```bash
git clone <repository-url>
cd leetcode-club
```

### 2. Create Your Branch

Before starting a contribution, update your local `main` branch.

```bash
git checkout main
git pull origin main
git checkout -b yourname/problem-name
```

Example:

```bash
git checkout -b busiso/two-sum
```

Use your own name or GitHub username in the branch name.

### 3. Solve and Submit

Solve and test the problem on LeetCode first. Once your solution passes, copy your Java solution into your own folder under the appropriate topic and problem.

For example:

```text
leetcode-club/
├── README.md
├── hashing-and-mapping/
│   ├── README.md
│   ├── PROBLEMS.md
│   └── solutions/
│       └── busiso/
│           └── two-sum/
│               ├── Solution.java
│               └── NOTES.md
└── prefix-sum/
    ├── README.md
    ├── PROBLEMS.md
    └── solutions/
```

Each contributor has their own folder, allowing multiple people to submit solutions to the same problem without overwriting each other's work.

Use `NOTES.md` to document your reasoning, complexity, mistakes, and lessons learned.

### 4. Commit and Push

Add only the files you intend to submit.

```bash
git add <path-to-your-solution>
git commit -m "Add two-sum solution (yourname)"
git push -u origin yourname/problem-name
```

### 5. Open a Pull Request

Open a Pull Request on GitHub targeting `main`.

Include a brief explanation of:

- **Understanding:** What is the problem asking?
- **Approach:** How did you derive your solution?
- **Complexity:** What are the time and space complexities?
- **Challenges:** What did you struggle with, and what did you learn?

### 6. Review and Merge

During our meetings, we review each other's Pull Requests, discuss different approaches, and provide constructive feedback.

A solution should be merged when it is correct, understandable, and has been reviewed. It does not have to be the most optimal solution we can imagine, provided its trade-offs are understood.

After merging, update your local repository before starting your next contribution.

```bash
git checkout main
git pull origin main
```

Then create a new branch for your next problem.

## Repository Structure

Each topic has its own folder.

- **Root `README.md`:** Our shared problem-solving process and contribution workflow.
- **Topic `README.md`:** The technique's core ideas, when to use it, and common mistakes.
- **`PROBLEMS.md`:** The selected problems for that topic.
- **`solutions/`:** Each contributor's Java solutions and learning notes.

## Club Rules

- Do not push directly to `main`.
- Create a branch and open a Pull Request for contributions.
- Attempt problems independently before looking at complete solutions.
- Review each other's code respectfully.
- Different correct approaches are welcome.
- Ask questions when something is unclear.
- Focus on understanding why a solution works, not just whether it passes.
- Explain your reasoning and learn from mistakes.

## Remember

We're not collecting accepted solutions. We're building the ability to understand problems, derive algorithms, write correct code, and apply what we've learned to unfamiliar challenges.

**The measure of progress is not how many problems we solve, but how independently we can solve the next one.**

Happy coding!