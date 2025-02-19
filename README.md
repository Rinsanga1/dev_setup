## My Dev Setup - Ubuntu

### What is this ?
a repo to recreate my dev workflow on any ubuntu based machine in 20 mins


### How does it work ?
a dumb bash script that is setup to install everthing i need ( like docker )
and then merge my env/.config file and done - rdy to code on a new system
just like that!


### How to setup ?

1. set DEV_ENV ( pwd because i know from where to run the script)
 ```export DEV_ENV=$(pwd) ```

2. run run to start installation on basics like node, docker, rust etc...
 ``` ./run ```

3. run dev_env to merge the .config ( they will merge so caution!)
 ``` ./dev_env ```

