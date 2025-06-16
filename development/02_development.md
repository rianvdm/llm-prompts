Use Claude Code for this

Adapted from [https://harper.blog/2025/05/08/basic-claude-code/](https://harper.blog/2025/05/08/basic-claude-code/).

## Development

`/init` to create `claude.md`. Read and edit, and add the text from [03_claude.md](/development/03_claude.md) in this repo. 

## For each session

1. Read `claude.md`, `spec.md`, `prompt_plan.md` and `todo.md`. Identify any prompts / items not marked as completed.
2. For each incomplete prompt:
    - Double-check if it's truly unfinished (if uncertain, ask for clarification).
    - If you confirm it's already done, skip it.
    - Otherwise, implement it as described. Before starting implementation, provide an ELI5 explanation of what you're about to do.
    - Make sure the tests pass, and the program builds/runs.
    - Update `todo.md` to mark this task as completed.
    - Commit the changes to the repository with a clear commit message.
3. After you finish each prompt, explain what you did and what should now be possible. If I am able to manually test the latest change myself to make sure it works, give me instructions on how I can do that.
4. Pause and wait for user review or feedback.
5. Repeat with the next unfinished prompt as directed by the user.