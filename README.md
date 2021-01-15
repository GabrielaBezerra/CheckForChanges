# Check For Changes

Simple Bash script for checking if a website has been updated. It's currently working on MacOS and Linux!

MacOS version uses `say` command to make the computer speak when the website has changed, while Linux uses `espeak`.

Thanks @NirvadoX for implementing a linux version 🐧 🎉


### Setup

Clone this repository, or copy/save the raw file.
```
git clone https://github.com/GabrielaBezerra/CheckForChanges.git
```

Make the script executable.
```
chmod +x check-for-changes
```


### Usage
```
./check-for-changes "<url>" "<message>" [<interval of update in seconds>]
```

#### Example
```
./check-for-changes "https://www.apple.com" "Hey, Apple site changed\!" 5
```
