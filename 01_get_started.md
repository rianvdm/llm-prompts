Use ChatGPT 4o for these, o3 if it's really complicated.

## Idea brainstorming

We are going to brainstorm an idea I have together. Ask me one question at a time (roughly 20-25 questions) so we can flesh it out in great detail. Challenge assumptions where needed to ensure the idea will meet user needs. Each question should build on my previous answers, and our end goal is to have a detailed specification I can hand off to a developer. Let’s do this iteratively and dig into every relevant detail. Remember, only one question at a time.

Here’s the idea:

---IDEA---

## Create spec

Now that we’ve wrapped up the brainstorming process, compile our findings into a comprehensive, developer-ready specification. I want to use the Cloudflare Workers development platform everywhere it's a viable choice. Include all relevant requirements, architecture choices, data handling details, error handling strategies, and a testing plan so a developer can immediately begin implementation. Use markdown for the spec.

> 💡 Create `/spec` folder, save as `spec.md`

## Create prompt plan

Draft a detailed, step-by-step blueprint for building this project based on the spec below. Then, once you have a solid plan, break it down into small, iterative chunks that build on each other. Look at these chunks and then go another round to break it into small steps. Review the results and make sure that the steps are small enough to be implemented safely with strong testing, but big enough to move the project forward. Iterate until you feel that the steps are right sized for this project.

From here you should have the foundation to provide a series of prompts for a code-generation LLM that will implement each step in a test-driven manner. Prioritize performance, best practices, incremental progress, and early testing, ensuring no big jumps in complexity at any stage. Make sure that each prompt builds on the previous prompts, and ends with wiring things together. There should be no hanging or orphaned code that isn't integrated into a previous step.

Make sure ypu separate each prompt section. Each prompt should be tagged as text using code tags. The goal is to output prompts, but context, etc is important as well. Use markdown.

Spec:

---INSERT SPEC---

> 💡 Save `prompt_plan.md` in `/spec`

## Create to do list

Now create a To Do list in markdown that I can use as a checklist for the project (spec and prompt plan). Be thorough.

> 💡 Save as `todo.md` in `/spec`