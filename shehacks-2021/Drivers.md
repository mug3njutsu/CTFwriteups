# CTF Name: Challenge name

![date](https://img.shields.io/badge/date-11.11.2021-brightgreen.svg)  
![solved in time of CTF](https://img.shields.io/badge/solved-in%20time%20of%20CTF-brightgreen.svg)  
![Forensic category](https://img.shields.io/badge/category-Forensic-lightgrey.svg)
![score](https://img.shields.io/badge/score-100-blue.svg)


## Description
What is the MD5 hash of the unextracted driver filesytem contained in the firmware?

Flag format is: Hackfest{answer}

## Attached files
- [demo.zip](./files/demo.zip)

## Summary
This was the first challenge i solved which had a little trick in it too that required precision carving. The challenge required us to get the md5 of the folder with drivers in the one of the squash file system.
## Flag
```
Hackfest{redacted}
```

## Detailed solution

This challenge required the use of binwalk and dd to successfully carve the filesystem. At first i tried extracting with binwalk and got a folder that contained drivers 
```
binwalk -e demo.bin
```
![image_info](./files/squashfs.png)

From the 

**Duis aute irure dolor** in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Another solutions
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
