# Session 1 - Installation, Setup & Introduction to Golang

## Installation Proto

### 1. Requirements

<details><summary>macOS</summary>
  
```bash
brew install git unzip gzip xz
```
  
</details>

<details><summary>Ubuntu / Debian</summary>
  
```bash
apt-get install git unzip gzip xz-utils
```
  
</details>

<details><summary>RHEL-based / Fedora</summary>
  
```bash
dnf install git unzip gzip xz
```
  
</details>

### 2. Installing

<details><summary>Linux, macOS, WSL</summary>
  
```bash
bash <(curl -fsSL https://moonrepo.dev/install/proto.sh)
```
  
</details>

<details><summary>Windows</summary>
  
```bash
irm https://moonrepo.dev/install/proto.ps1 | iex
```
You may also need to run the following command for shims to be executable:
```bash
Set-ExecutionPolicy RemoteSigned

# Without admin privileges
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```
  
</details>









