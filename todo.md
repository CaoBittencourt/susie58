# Todo

Our approach to project management here is drastically simplified.
We don't use any unnecessary, bloated, software for tracking tasks etc.

This is how we work:

1. in the "Goal" section below we provide a general intuition of our mission statement;
2. after that, in "Warnings", we list some conventions for commiting to the project, at least in its current iteration;
3. and the final "Checklist" is our inventory of tasks, which may or may not be thoroughly detailed.

Note tasks can be both macro (project-level) and micro (execution-level) in scope. Thus, we assume a potentially infinite number of subdivisions, making concepts such as "epics", "user stories" and the like completely irrelevant. Simply write out what needs to be done and further specify it within nested lists of subtasks, subsubtasks etc if and when appropriate.

Finally, task status is denoted with:
- [o] for currently active task
- [/] for started, but not currently active
- [x] for finished
- [-] for canceled
- [?] for uncertain (whether to implement)
- [!] for warnings

# Goal
The perfect ZMK config for Lily58.

# Warnings

# Checklist
- [ ] actual config
    - [ ] thumb clusters
    - [ ] abnt2 support
    - [ ] arrows on jlik (left-right-up-down)
        - [ ] toggle some key for page controls (e.g. page up, page down etc)
            - [?] invert arrows with page controls
    - [?] numpad layer: 789uoijklm., 
    - [ ] invert numbers and symbols at the top row
        - [?] or use top row for something else entirely
- [x] initial sketch
    - [x] setup repo
    - [x] get abnt2 header
    - [x] setup build.yaml
    - [x] create keymap
    - [x] compile firmware