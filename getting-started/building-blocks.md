Truffle is a technology platform that empowers users with the capacity to
perform **Tasks** by instructing and **Agent** to use the **Tools** within an
**App.** Let’s walk through each step of the typical flow for a **Task**.

## Step 1: Agent selects an App based on the user’s prompt

An Agent is the artificial intelligence which will build and execute a plan to
accomplish the intent behind the user’s prompt. To accomplish the goal, the
**Agent** parses the prompt and selects an **App** to use to solve this problem.

For our example, we can imagine the Agent comparing the prompt to its
understanding of each **App** and selecting the one which seems the most apt:

[user providing prompt](prompt.png)

## Step 2: Agent selects and uses Tools to accomplish goal

Apps are two things: a bundle of software-based functions and a scratchpad to
store intermediate work. When an Agent selects an App, it receives an inventory
of Tools—the software functions—and it then executes a plan to accomplish the
goal. 


## Step 3: Agent returns Deliverable

When applicable, the **Agent** then returns the results of its work to the user.
This can be in the form of a text response or file. When the **Agent** is
uncertain of how to proceed, it will prompt the user for more information.
