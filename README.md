🔹 Setup & Configuration:
| Command | Use Case |
| --- | --- |
| ``git ``config ``--global ``user.name ``"Your ``Name"`` | Set your username globally |
| ``git ``config ``--global ``user.email ``"you@example.com"`` | Set your email globally |
| ``git ``config ``--list`` | Verify configuration |



🔹 Repository Initialization:
| Command | Use Case |
| --- | --- |
| ``git ``init`` | Initialize a new local repository |
| ``git ``clone ``<repo_url></repo_url>`` | Clone an existing remote repository |

🔹 Basic File Operations:
| Command | Use Case |
| --- | --- |
| ``git ``status`` | Check current repo status |
| ``git ``add ``<file></file>`` | Stage a specific file |
| ``git ``add ``.`` | Stage all changes |
| ``git ``commit ``-m ``"message"`` | Commit staged changes |
| ``git ``commit ``-am ``"message"`` | Add & commit tracked files in one step |

🔹 Branching & Switching:
| Command | Use Case |
| --- | --- |
| ``git ``branch`` | List all branches |
| ``git ``branch ``<branch_name/>`` | Create a new branch |
| ``git ``checkout ``<branch_name/>`` | Switch to a branch |
| ``git ``checkout ``-b ``<branch_name/>`` | Create & switch to new branch |
| ``git ``switch ``<branch_name/>`` | Modern way to switch branches |
| ``git ``switch ``-c ``<branch_name/>`` | Modern way to create & switch |

🔹 Merging & Rebasing:
| Command | Use Case |
| --- | --- |
| ``git ``merge ``<branch_name/>`` | Merge branch into current branch |
| ``git ``rebase ``<branch_name/>`` | Reapply commits on top of another branch |
| ``git ``cherry-pick ``<commit_hash></commit_hash>`` | Apply a specific commit to current branch |

🔹 Remote Repository Operations:
| Command | Use Case |
| --- | --- |
| ``git ``remote ``-v`` | View remote URLs |
| ``git ``remote ``add ``origin ``<url></url>`` | Add a new remote |
| ``git ``remote ``set-url ``origin ``<url></url>`` | Change remote URL |
| ``git ``fetch ``origin`` | Fetch changes without merging |
| ``git ``pull ``origin ``main`` | Fetch & merge changes from remote |
| ``git ``push ``origin ``main`` | Push local commits to remote |


🔹 Tagging:
| Command | Use Case |
| --- | --- |
| ``git ``tag`` | List all tags |
| ``git ``tag ``v1.0`` | Create a lightweight tag |
| ``git ``tag ``-a ``v1.0 ``-m ``"message"`` | Create an annotated tag |
| ``git ``push ``origin ``v1.0`` | Push tag to remote |



🔹 Stashing:
| Command | Use Case |
| --- | --- |
| ``git ``stash`` | Save uncommitted changes temporarily |
| ``git ``stash ``list`` | View stashed changes |
| ``git ``stash ``apply`` | Reapply stashed changes |
| ``git ``stash ``drop`` | Delete a stash |

🔹 Undo & Reset:
| Command | Use Case |
| --- | --- |
| ``git ``reset ``<file></file>`` | Unstage a file |
| ``git ``reset ``--hard ``HEAD`` | Discard all local changes |
| ``git ``revert ``<commit_hash></commit_hash>`` | Create a new commit that undoes changes |
| ``git ``checkout ``-- ``<file></file>`` | Restore file from last commit |

🔹 Logs & History:
| Command | Use Case |
| --- | --- |
| ``git ``log`` | View commit history |
| ``git ``log ``--oneline`` | Compact commit history |
| ``git ``diff`` | Show changes not staged |
| ``git ``diff ``--staged`` | Show staged changes |



🔹 Collaboration & Troubleshooting:
| Command | Use Case |
| --- | --- |
| ``git ``pull ``origin ``main ``--allow-unrelated-histories`` | Merge unrelated histories |
| ``git ``fetch ``--all`` | Fetch all branches |
| ``git ``reset ``--hard ``origin/main`` | Force local branch to match remote |
| ``git ``reflog`` | View all actions (useful for recovery) |


# All-Git-Commands
