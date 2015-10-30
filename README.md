# gdp-submodules
GDP setup using git submodules

--- 

This is pretty close to ready for public usage :-)

---- 

The project uses submodules to pull in dependencies

It is therefore recommended to :

```bash
git clone --recursive <thisrepo> -b <branch>
```
where branch is (for example) koelsch, porter or minnowboard
(you must check which branches exist)

The master branch is no longer maintained

If you forgot the recursive option, try:
```bash
git checkout <branch>
git submodule init
git submodule update
```

To build:
```
source init.sh
```
and then follow instructions

If you do anything more advanced you probably need to study
information on git submodules - they are a bit special to
work with...

One recommendation to improve usability a little: 
```bash
git config diff.submodule log
```
