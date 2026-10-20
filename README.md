# Applied Robotics and AI Coursework

Coursework repository for **Applied Robotics and AI Project**, BEng (Hons) Robotics and Artificial Intelligence, University of Hertfordshire.

## Assignment 1: Setting up the workspace

This repository contains the Git workflow documentation and written discussion for the workspace assignment. It is separate from the [C-RAM Desktop Camera Tracker project](https://github.com/kingdominick343-dev/c-ram-desktop-tracker).

- `Assignment_01_Git_Discussion.txt`: explanation of Add, Commit and Push.
- `README.md`: setup, practical workflow, branching and submission checklist.
- Existing project management board: https://trello.com/b/itvwndWJ/c-ram-desktop-camera-tracker

## Setup and Git demonstration

Install Git and authenticate with your own GitHub account. Run the following in a terminal; these are demonstration instructions, not a claim that the commands have already been performed.

```sh
git clone https://github.com/kingdominick343-dev/applied-robotics-ai-coursework.git
cd applied-robotics-ai-coursework
git switch -c coursework/git-practice
```

Create `practice.txt` in a text editor and write a short note about what you learned. Save it, then run:

```sh
git status
git add practice.txt
git diff --cached
git commit -m "Add Git practice notes"
git push -u origin coursework/git-practice
```

Edit the note and save again. Review and record the change:

```sh
git diff
git add practice.txt
git commit -m "Explain the difference between local and remote history"
git push
git log --oneline
```

Open a pull request from `coursework/git-practice` to `main`, review the changes, and merge when ready. Synchronize the local main branch:

```sh
git switch main
git pull --ff-only
```

## Branching strategy

`main` contains reviewed coursework documentation. Use a short-lived branch such as `coursework/git-practice` for each exercise or change, commit meaningful steps, and review through a pull request before merging. The `docs/assignment-01` branch is an initial workspace branch; it is not evidence of a completed terminal exercise.

## Evidence and submission

The assignment asks for a 5–10 minute video (maximum 10 minutes), a written Git discussion, a populated project management board, a repository shared with the lecturer, a branch, and evidence of ongoing use. The stated deadline is 20 October 2026 at 11:30pm.

Before submission:

- Demonstrate actual Add, Edit, Commit, Push and Clone operations in the video.
- Explain Add vs Commit vs Push using the accompanying text file.
- Show the repository, branch and meaningful commit history.
- Show the existing project board and its real workflow and updates.
- Confirm lecturer access to the repository and board using the lecturer contact in the assignment brief.
- Submit the video, written discussion and required links through the course submission channel.

Record genuine progress as work happens. A newly created repository does not establish earlier continuous use. Keep actual screenshots, commit links and dated notes, and explain the relationship to the existing project repository where relevant. Video recording, lecturer invitations, terminal demonstrations and submission are still pending unless completed separately.
