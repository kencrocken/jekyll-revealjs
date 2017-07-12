## Bash Scripts

Write scripts in `~/.bash_profile`  

- A little more pleasant and efficient {% fragment %}
- Add some colors and display the current git branch and status {% fragment %}

note:
- .bashrc, non-login shell
- some say to consolidate custom bash scripts in .bashrc, I haven't  

--

## The Prompt

Bash prompt can be customized by changing the values of bash PS1, PS2, PS3, PS4 variables.

``` bash
echo "Bash PS1 variable:"  $PS1
echo "Bash PS2 variable:"  $PS2 
```

note:
- The PS1 prompt is the primary prompt,
- PS2 is the secondary prompt
- PS3, PS4 deal with select prompts
- switch to command line and show the variables.
