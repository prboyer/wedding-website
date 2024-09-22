Original Knot website URL
[https://www.theknot.com/us/haley-tollison-and-paul-boyer-oct-2024](https://www.theknot.com/us/haley-tollison-and-paul-boyer-oct-2024)

## Donwload Index File (Home Page)
This needs to be downloaded manually. Page source downloaded from navigating to the page in the browser and choosing *View Source*. 

## Download Website Subfiles
```bash
wget -kp --no-parent -e robots=off https://www.theknot.com/us/haley-tollison-and-paul-boyer-oct-2024 -nH -r
```
### Set Subfile Extensions
```bash
find ./us/haley-tollison-and-paul-boyer-oct-2024 -type f -exec mv {} {}.html \;        
```

