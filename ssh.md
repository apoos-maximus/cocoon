some helpful links :
#### about the `known_hosts` file :
https://security.stackexchange.com/questions/20706/what-is-the-difference-between-authorized-keys-and-known-hosts-file-for-ssh/20710
#### github's documentation ---- gasp's its nice ....ppphew !!
https://help.github.com/articles/connecting-to-github-with-ssh/

# GENERATING SSH KEYS for your machine
command :
`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
`

````
Generating public/private rsa key pair.
Enter a file in which to save the key (/home/you/.ssh/id_rsa): [Press enter]
Enter passphrase (empty for no passphrase): [Type a passphrase]
Enter same passphrase again: [Type passphrase again]
````

# ADDING TO SSH agent

 ### start ssh-agent in background
    `eval "$(ssh-agent -s)"
    `
 ### add ssh private key to ssh agent
    `ssh-add ~/.ssh/id_rsa
    `
 ### add SSH key to your github account
