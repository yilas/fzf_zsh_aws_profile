# fzf_zsh_aws_profile
fzf-based AWS Profile setter for zshell. Binds to a key (CTRL+B), allowing you to quickly switch between AWS profiles. Works great for situations where you have lots of AWS profiles defined (e.g. SSO or role-base environments).

## Install
```bash
wget https://raw.githubusercontent.com/richstokes/fzf_zsh_aws_profile/main/fzf_zsh_aws_profile -O ~/.aws/fzf_zsh_aws_profile
echo "" >> ~/.zshrc
echo "#fzf_zsh_aws_profile" >> ~/.zshrc
echo "source ~/.aws/fzf_zsh_aws_profile" >> ~/.zshrc
```

## Usage
Ctrl-B->pick profile->type aws command->[enter]

## Credits
Copied/modified from the [bash version](https://github.com/stonematt/fzf_aws_profile/blob/main/fzf_aws_profile)
