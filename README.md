# fzf_aws_profile
bash key binding to fzf across aws profiles before running aws cli


We use aws profiles to restrict access and manage permissions on aws cli.  As a result, we have a bit of explosion of AWS_PROFILES that we might inject into an `aws` command.  This helper will let use fzf to search and select from your profiles inline while on the bash command line.

## Example

  ![](https://raw.githubusercontent.com/stonematt/i/main/fzf_aws_profile/fzf_aws_profile.gif)

## Usage

This happens to be bound to Ctrl-b, so:

* Ctrl-b
* search for aws profile
* select enter to choose one
* finish typing aws command or alias.

## Special thanks

Thanks to https://github.com/junegunn/fzf/
