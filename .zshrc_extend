alias zshrc='gedit ~/.zshrc &'
alias zource='source ~/.zshrc'

newalias() {
    if [ "$#" -ne 2 ]; then
        echo "Usage: newalias <alias_name> <command>"
        return 1
    fi
    echo "alias $1='$2'" >> ~/.zshrc
    alias $1="$2"
    echo "Alias '$1' created for command '$2'"
}
