# Version Control Lesson 1: Reflections
https://classroom.udacity.com/courses/ud775

### How did viewing a diff between two versions of a file help you see the bug that was introduced?

Using `diff` was obviously more useful than visually scanning a long file, because it immediately calls out the (sometimes) minute differences in a file, in a matter of seconds.

The syntax was perhaps a little obtuse, but it works in a pinch.

### How could having easy access to the entire history of a file make you a more efficient programmer in the long term?

- You can be more self-aware about your coding process, when you see how you begin and finish a program
- You can review and reflect upon your code
- It's hard to lose data accidentally
- You can more easily fix issues that come up when sharing a single file between muliple devs
- You can more easily go back to earlier ideas, if your programming path takes a wrong turn.

### What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

**Pros of manual commits**
- Logical review points
- You can make the commits more/less granular when working on varying levels of complexity
- It's less messy

**Pros of automatic saving**
- It doesn't matter if you forget to save
- There's a regular time-based record of your progress
- You don't need to expend effort on recording progress

### Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

The use case for tools like Git is predominantly for groups of files that work together towards a common goal. While Google documents (et al) may consist of multiple files that are packaged together, they don't actually rely on each other to "work". And they are designed to be read individually.

### How can you use the commands git log and git diff to view the history of files?

When using Git, `git log` will show you a history of all the git commits that have been made on that file. You can scroll up and down to view more. Take a look at `git help log` under *Pretty Formats* to see some options for formatting. I recommend using `git log --graph --oneline`, especially when you have a bigger history, with multiple merges.

Use `git diff commitID1 commitID2` to compare the differences between two commits. The pluses and minuses show what has been added and removed from the file(s) in question.

### How might using version control make you more confident to make changes that could break something?

Obviously, you don't have the fear that you're not going to be able to recover your old code, so all new efforts will either push you forward, or you can "rewind" back to your last clean version. It's similar to playing computer games, where you save your progress to a point you're happy with, then do whatever you like, knowing that you can always come back and restart from your saved position. :)

It gives you more creative freedom, unleashing your brain by removing your inhibitions based on failure.













