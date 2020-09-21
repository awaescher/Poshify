# PowerShell

## Aliases

#### Installation
 - Open PowerShell, type `notepad $PROFILE` and hit enter.
 - Add the functions from the ps1-file of this repository, save and close notepad.
 - Restart PowerShell.

### [Cake Build] Invokce-Cake: `cake`
Finds a Cake script like `build.ps1` and executes a given task. 

```
cake Release                // maps to ".\build.ps1 -Target Release"
```

`cake` runs the directory tree **upwards** to find a Cake script. This means it can be used in any subfolder of a project using Cake build.

### [git] Push-Upstream: `pu`
Dynamically builds and invokes the full git command to push to a new upstream:

![pu](../img/pu.png)

### [git] Browse-Remote: `br`
Dynamically builds the remote URL of the current branch and opens it with the default browser:

![br](../img/br.png)

### [git] Push-Upstream-And-Browse-Remote: `pubr`
Chains both of the prior commands. This comes very handy if you are pushing new branches regularly to create Pull-Requests afterwards in the web UI of your repository.

It pushes your local commits to a new upstream branch and opens the web UI afterwards from which you should be able to create a Pull-Request with just a few mouse clicks.