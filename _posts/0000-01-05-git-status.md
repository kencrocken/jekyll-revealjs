## Git Status  

Is there something to commit?  Add an asterik.

```bash
# ~/.bash_profile
...
function parse_git_status() {
  local git_status="$(git status --porcelain 2> /dev/null)"
  if [[ $git_status != "" ]]; then
    echo -n "*" 
  else
    echo -n ""
 fi
}

export PS1=" ... \$(parse_git_status) $ "

```

note: 
- sed, stream editor
- echo -n (trims trailing newline)

