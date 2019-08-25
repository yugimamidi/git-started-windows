# Git Started on Windows

> Get your Windows computer ready for collaboration with Git

- [Webpage](https://github.com/denisecase/git-started-windows)
- [Source](https://denisecase.github.io/git-started-windows/)

## Prerequisites

- [Windows Setup for Developers](https://github.com/denisecase/windows-setup)
- [Windows File Management](https://github.com/denisecase/windows-file-management)
- [Basic Tools for Web Development](https://github.com/denisecase/basic-tools-for-webdev)

## Git

Git is a distributed version control system that allows developers to work together on common projects and collaborate effectively with people around the world.

## Repositories

A repository is a place to store content. This project is kept in a public repository at <https://github.com/denisecase/git-started-windows>.

Repositories may also be private - visible only to yourself or to a team.

## Cloud Storage Providers

There are many places to store your content while you collaborate. We will set up accounts with two very popular providers.

- [GiHub](https://github.com/)
- [BitBucket](https://bitbucket.org)

Both are widely used and it can be helpful to have accounts in both places. As you create new repositories for yourself or a team, you can decide which one is a better choice for each project.

If you're a student, check both sites for the most recent education options.

- [GitHub Education](https://education.github.com/)
- [BitBucket Education](https://bitbucket.org/product/education)

## Install Git for Windows

Work through [Basic Tools for Web Development](https://github.com/denisecase/basic-tools-for-webdev). Or install Git for Windows from <https://git-scm.com/download/win>. The 64-bit version is recommended for most users.

## Set up Git

It is critical that you follow all setup instructions. You must configure Git with your full name and email address.

## Install TortoiseGit

If you haven't already, install TortoiseGit from <https://tortoisegit.org/>. TortoiseGit integrates with Windows File Explorer, making it fast and easy to execute most of the typical Git commands used every day.

## Transferring Files

There are two methods for transferring files from our computer to the cloud: HTTP and SSH. They offer two different ways of providing authentication and authorization.

- HTTP - to exchange files, we enter an email and password with each transfer.
- SSH - we set up a public/private key pair between our computer and cloud account once at the begining and do not need to type a password with each transfer.

## Install Putty for SSH

To enable the SSH option, we need to be able to generate a pair of keys. One public key that is kept in our account in the cloud and a private key that is kept on our machine.

Install PuTTY from <https://www.ssh.com/ssh/putty/download>.

PuTTY includes PuTTYgen, a utility program that helps create SSH key pairs.

## SSH Public-Private Key Pairs

When I work, I use:

- Different emails
- Different computers
- Different cloud storage providers

I create a public-private key pair for every email-computer-cloud combination. For each combination, I'll create a .ppk (private key) and a .pub (public key) pair. The .pub keys are optional - if you use PuTTYgen to open your .ppk, it will show you the public key. You'll copy and paste the public key into your cloud account / settings / ssh keys.

For example, with a desktop and a laptop, I might have keys named:

```PowerShell
denisecase-pc1-bitbucket.ppk
denisecase-pc1-bitbucket.pub
denisecase-lappie1-bitbucket.ppk
denisecase-lappie1-bitbucket.pub
denisecase-pc1-github.ppk
denisecase-pc1-github.pub
denisecase-lappie1-github.ppk
denisecase-lappie1-github.pub
dcase-lappie2-github.ppk
dcase-lappie2-github.pub
```

This naming convention keeps keys organized.

## Create SSH Key Pairs & Add Public Keys To Cloud Accounts

Use Windows start to run PuTTYgen. Follow the instructions from the link below to create private keys that will be stored in your .ssh folder and corresponding public keys to be added to your BitBucket or GitHub accounts.

- <https://github.com/RedWingedJerbear/GitSSHTuttorial>

Make sure your computer is set up for developers and that you can see hidden files [1].

## Terms

- Cloud storage provider
- BitBucket
- GitHub
- Git
- TortoiseGit
- Repository/repo
- HTTP
- SSH
- SSH key pairs
- Private key
- Public key
- PuTTyGen - a graphical tool to create SSH keys

## Trouble Shooting Tips

- [Git Clone not working with private repo](https://github.community/t5/How-to-use-Git-and-GitHub/git-clone-is-not-working-for-a-private-repo/td-p/2513)
- [Configuring multiple email accounts](https://simonbasle.github.io/2017/10/git-identities-and-ssh/)

## Next Steps

Upgrade git automagically

- [Automate daily upgrades](https://github.com/denisecase/windows-daily-software-upgrade)

## See Also

- [Setting Up for Professional Software Development](https://github.com/denisecase/pro-dev-list)
