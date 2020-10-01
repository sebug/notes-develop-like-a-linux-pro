# Notes TechTalkThursday: Develop Like A Linux Pro on Windows
Eric Funk, 2020-10-01

## Developers, Developers, Developers!
History:

- Cygwin
- PHP on IIS

:-(

2014 Satya Nadella: Microsoft loves Linux

Then: WSL

2020: WSL 2: no longer translating syscalls, using a VM

"It gets harder and harder to hate those guys"

## Demo Time: Ubuntu on Windows
Download Ubuntu on the Windows Store

Edit your bashrc in Notepad

Run Docker for WSL (it's an Option on Docker to use WSL2)

The network is completely transparent between WSL and Windows

### VS Code
Connect thingie for WSL, then open terminal and there you go

Oddity: VS code plugins for WSL or Windows

File system is fast, faster than MacOS in his opinion

Also nice: kubectl still in there

# Second Talk: Project Syn

Why manage so many Kubernetes clusters?

Git repository per cluster

Uses quite a lot of tools

- Argo CD
- Kapitan

https://syn.tools/syn/tutorials/getting-started.html

