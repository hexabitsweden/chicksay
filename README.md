# chicksay

A cowsay clone with a twist..

## Getting Started
Donwload and extract. Or clone from this site.
```
chmod +x chicksay
```
And then
```
cp chicksay /usr/local/bin/ or /usr/bin/
```
Help
```
chicksay -h (or just chicksay)
```
Example 1
```
date | chicksay -eva yellow
```
Example 2
```
uname -a | chicksay -lisa yellow
```
Example 3 (Text Animation)
```
cat /etc/passwd | chicksay -eva yellow
```
Example 4
```
cat /etc/passwd | chicksay -man green (will show a naked man, reading passwd)
```
Girls 
```
lisa
anna
eva
vendela
angelina
```
Others:
```
homer
fish
alien
```
Colors
```
magenta
yellow
brown
cyan
red
```

### Prerequisites

Only tested on FreeBSD (Developed on FreeBSD 8) and a couple of Linux distros.
Does not work with colors on ZSH and on default Mac os terminals. 

## Running
![Image of Lisa](https://github.com/hexabitsweden/chicksay/blob/master/screenshots/Lisa.png?raw=true)

## License

This project is licensed under the BSD License

## Acknowledgments
* I made this as a joke for my friends terminal seven years ago. 
* I apologize in  advance, i know this is not politically correct
* Not politically correct
* Not suited for work

For more info: http://blog.codeland.se

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDACOFym6/3v7eVZ1L+GFncnRKKUdBJrhv8wbqK1LP2JpgGXl8uMFdVHxsuZ29OrB2NtQGq/T9STsa3TjdxAPoe2N5wRCW+Kyfdi8PIofuG8JjqjK5WkOg6BPdzGTcXxsZc/50fEzz7+GaHrEUlWwvmG4h1ASPrxMC0n2z7wmtagYGf34GOy/m1ntcASAoHj8KEK7wlJoGiYtgfW+mtsaqtVUh3vNR5hK2Yc60yUWOJ7ftHjpxzazSAjwjtcTqwz/JwAU0la9ozExoJAW0wmwxBFi4jnjYYY9AKNaRIYSTooPlgPHcNalujONf0pv3fuuVRtzlyo//qejC53SbcXx+JCAn3p3Mi24ddUrb9V5g/XQuZKLqWFV+QrCvng/6huXSNP55XoUYG9de/h5fuB8vMji94iS4+oVfgpcffVLBRwjeMWaOAxX4ngc8yBQtnpul66QJ3ocSfWBDG5kxQsZSKxZTy6tyEZYphMJ5+t6L51jb2tR9fkB+9BIdjkB+E+MU= hexabit@Daniels-Mac-mini.local
