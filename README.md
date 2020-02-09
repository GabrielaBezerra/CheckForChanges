# Check For Changes

Simple Bash script for checking if a website has been updated. Since it uses "say" script to notify changes on the specified website, I guess it will only work properly on macOS. I'm going to check/improve that soon.

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
