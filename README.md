# cpueval
### Description
Limit process cpu usage. This script is essentially a wrapper for `cpulimit`

### Usage
`./cpueval <command_to_execute> <max_percentage_of_cpu_usage>`
Ex: `./cpueval "echo 'Hello World!" 10`
ex: `./cpueval ./some_script 50`

### Motivation
I wrote a program to generate a wordlist, but the program was making my laptop get loud and heat up. I looked at the task manager and saw that the program had a cpu usage of 94%! I needed a way to find a way to reduce the program's cpu usage so that I wouldn't damage my laptop.

### Dependencies
cpulimit
