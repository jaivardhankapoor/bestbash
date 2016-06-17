# PS1 CONFIG {{{
[[ -f $HOME/.dircolors ]] && eval $(dircolors -b $HOME/.dircolors)
if $_isxrunning; then

  [[ -f $HOME/.dircolors_256 ]] && eval $(dircolors -b $HOME/.dircolors_256)

  export TERM='xterm-256color'

  B='\[\e[1;38;5;33m\]'
  LB='\[\e[1;38;5;81m\]'
  GY='\[\e[1;38;5;242m\]'
  G='\[\e[1;38;5;82m\]'
  P='\[\e[1;38;5;161m\]'
  PP='\[\e[1;38;5;93m\]'
  R='\[\e[1;38;5;196m\]'
  Y='\[\e[1;38;5;214m\]'
  W='\[\e[0m\]'

  get_prompt_symbol() {
    [[ $UID == 0 ]] && echo "#" || echo "\$"
  }

  if [[ $PS1 && -f /usr/share/git/git-prompt.sh ]]; then
    source /usr/share/git/completion/git-completion.bash
    source /usr/share/git/git-prompt.sh

    export GIT_PS1_SHOWDIRTYSTATE=1
    export GIT_PS1_SHOWSTASHSTATE=1
    export GIT_PS1_SHOWUNTRACKEDFILES=0

    export PS1="$GY[$Y\u$GY@$P\h$GY:$B\W\$(__git_ps1 \"$GY|$LB%s\")$GY]$W\$(get_prompt_symbol) "
  else
    export PS1="$GY[$Y\u$GY@$P\h$GY:$B\W$GY]$W\$(get_prompt_symbol) "
  fi
else
  export TERM='xterm-color'
fi
#}}}



# COLORED MANUAL PAGES {{{
# @see http://www.tuxarena.com/?p=508
# For colourful man pages (CLUG-Wiki style)
if $_isxrunning; then
  export PAGER=less
  export LESS_TERMCAP_mb=$'\E[01;31m'       # begin blinking
  export LESS_TERMCAP_md=$'\E[01;38;5;74m'  # begin bold
  export LESS_TERMCAP_me=$'\E[0m'           # end mode
  export LESS_TERMCAP_se=$'\E[0m'           # end standout-mode
  export LESS_TERMCAP_so=$'\E[38;5;246m'    # begin standout-mode - info box
  export LESS_TERMCAP_ue=$'\E[0m'           # end underline
  export LESS_TERMCAP_us=$'\E[04;38;5;146m' # begin underline
fi
#}}}
