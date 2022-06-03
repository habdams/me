01 Jun 2022 11:45:06

_Work Log_
- Set up prettier: with configuration below.

```
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true
}
```
- Git clone console repo
- Ran into error 'module not found: DockPlugin'

#### Fix
**Because it's a sub module**
- run `git submodule init`
- then run `git submodule update`


- Had a quick walkthrough of how to use Shortcuts(Project management app)

_Quick Tip from Patricia_:
- Raise a PR from SHortcut, it prepopulate the PR form on github and it's easy for shortcut to track PR's that way. 

#### Reference
-  [Sub modules in git](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
