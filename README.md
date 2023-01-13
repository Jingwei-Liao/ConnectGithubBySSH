# ConnectGithubBySSH

## Step1: Generate ssh-key
    ssh-keygen

## Step2: Display the public key
    cat ~/.ssh/id_rsa.pub

## Step3: Copy the public key to your github account setting
    https://github.com/settings/keys

## Step4: Test the SSH key
    ssh -T git@github.com
