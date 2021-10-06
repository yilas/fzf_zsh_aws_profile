# fzf_zsh_aws_profile
fzf-based AWS Profile setter for zshell.

## Install
```bash
wget https://raw.githubusercontent.com/richstokes/fzf_zsh_aws_profile/main/fzf_zsh_aws_profile -O ~/.aws/fzf_zsh_aws_profile
echo "" >> ~/.zshrc
echo "#fzf_zsh_aws_profile" >> ~/.zshrc
echo "source ~/.aws/fzf_zsh_aws_profile" >> ~/.zshrc
```

## Usage
Ctrl-b->pick profile->type aws command->[enter]

## Credits
Copied/modified from the [bash version](https://github.com/stonematt/fzf_aws_profile/blob/main/fzf_aws_profile)
