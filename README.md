# Git_command
<br>


<table>
    <caption><b>Getting & Creating Projects</b></caption>
    <tr>
        <th>Command</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>git init</code></td>
        <td>Initialize a local Git repository</td>
    </tr>
    <tr>
        <td><code>git clone ssh://git@github.com/[username]/[repository-name].git</code></td>
        <td>Create a local copy of a remote repository</td>
    </tr>
</table>

<table>
    <caption><b>Basic Snapshotting</b></caption>
    <tr>
        <th>Command</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>git status</code></td>
        <td>Check status</td>
    </tr>
    <tr>
        <td><code>git add [file-name.txt]</code></td>
        <td>Add a file to the staging area</td>
    </tr>
    <tr>
        <td><code>git add -A</code></td>
        <td>Add all new and changed files to the staging area</td>
    </tr>
    <tr>
        <td><code>git commit -m "[commit message]"</code></td>
        <td>Commit changes</td>
    </tr>
    <tr>
        <td><code>git rm -r [file-name.txt]</code></td>
        <td>Remove a file (or folder)</td>
    </tr>
</table>

<table>
    <caption><b>Branching & Merging</b></caption>
    <tr>
        <th>Command</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>git branch</code></td>
        <td>List branches (the asterisk denotes the current branch)</td>
    </tr>
    <tr>
        <td><code>git branch -a</code></td>
        <td>List all branches (local and remote)</td>
    </tr>
    <tr>
        <td><code>git branch [branch name]</code></td>
        <td>Create a new branch</td>
    </tr>
    <tr>
        <td><code>git branch -d [branch name]</code></td>
        <td>Delete a branch</td>
    </tr>
    <tr>
        <td><code>git push origin --delete [branch name]</code></td>
        <td>Delete a remote branch</td>
    </tr>
    <tr>
        <td><code>git checkout -b [branch name]</code></td>
        <td>Create a new branch and switch to it</td>
    </tr>
    <tr>
        <td><code>git checkout -b [branch name] origin/[branch name]</code></td>
        <td>Clone a remote branch and switch to it</td>
    </tr>
    <tr>
        <td><code>git branch -m [old branch name] [new branch name]</code></td>
        <td>Rename a local branch</td>
    </tr>
    <tr>
        <td><code>git checkout [branch name]</code></td>
        <td>Switch to a branch</td>
    </tr>
    <tr>
        <td><code>git checkout -</code></td>
        <td>Switch to the branch last checked out</td>
    </tr>
    <tr>
        <td><code>git checkout -- [file-name.txt]</code></td>
        <td>Discard changes to a file</td>
    </tr>
    <tr>
        <td><code>git merge [branch name]</code></td>
        <td>Merge a branch into the active branch</td>
    </tr>
    <tr>
        <td><code>git merge [source branch] [target branch]</code></td>
        <td>Merge a branch into a target branch</td>
    </tr>
    <tr>
        <td><code>git stash</code></td>
        <td>Stash changes in a dirty working directory</td>
    </tr>
    <tr>
        <td><code>git stash clear</code></td>
        <td>Remove all stashed entries</td>
    </tr>
</table>
