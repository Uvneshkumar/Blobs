#   Initial One-Time Setup
```
    mkdir -p ~/aosp
    cd ~/aosp
    git clone https://github.com/ponces/treble_aosp -b android-16.0
    cd treble_aosp
    git remote add uvnesh https://github.com/Uvneshkumar/treble_aosp.git
    git fetch uvnesh
    git cherry-pick 9f7121d27d3172c2e74bd9849e1236bef653f032
    cd ~/aosp
```

#   Build
```
    bash treble_aosp/build.sh
```
