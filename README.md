# Git Started on Windows

> Get your Windows computer ready for collaboration with Git

- [Webpage](https://github.com/denisecase/git-started-windows)
- [Source](https://denisecase.github.io/git-started-windows/)

## Prerequisites

- [Windows Setup for Developers](https://github.com/denisecase/windows-setup)
- [Windows File Management](https://github.com/denisecase/windows-file-management)
- [Get Setup With Chocolatey](https://github.com/denisecase/get-setup-with-chocolatey)

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

## Education Discounts & Offers

If you're a student, check both sites for the most recent offers.

- [GitHub Education](https://education.github.com/)
- [BitBucket Education](https://bitbucket.org/product/education)
- [Microsoft Imagine](https://www.microsoft.com/en-cy/imagine)

## Install Git for Windows

Install Git for Windows from <https://git-scm.com/download/win>. The 64-bit version is recommended for most users.

## Set up Git

Follow all installation and setup instructions. You'll have to configure Git with your full name and email address.

## Install TortoiseGit

Install TortoiseGit from <https://tortoisegit.org/>. TortoiseGit integrates with Windows File Explorer, making it fast and easy to execute most of the typical Git commands used every day.

## Transferring Files

There are two methods for transferring files from our computer to the cloud: HTTP and SSH. They offer two different ways of providing authentication and authorization.

- HTTP - to exchange files, we enter an email and password with each transfer.
- SSH - we set up a public/private key pair between our computer and cloud account once at the begining and do not need to type a password with each transfer.

## Install Putty for SSH

To enable the SSH option, we need to be able to generate a pair of keys. One public key that is kept in our account in the cloud and a private key that is kept on our machine.

Install Putty from <https://www.ssh.com/ssh/putty/download>.

Putty includes PuttyGen, a tool for creating SSH key pairs.

## SSH Public-Private Key Pairs

When I work, I use:

- Different emails
- Different computers
- Different cloud storage providers

I create a public-private key pair for every email-computer-cloud combination. For each combination, I'll create a .ppk (private key) and a .pub (public key) pair.

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

Use Windows start to run PuttyGen. Follow the instructions below to create private keys that will be stored in your .ssh folder and corresponding public keys to be added to your BitBucket or GitHub accounts.

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

## References

1. [Windows Setup for Developers](https://github.com/denisecase/windows-setup)
