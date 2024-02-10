#### 01/2017: First version.
#### 02/2024: Cleaned up for CS2, still needs to be adapted.

##### Folder : 
```
$ /home/<user>/.steam/steam/userdata/<user id>/730/local/cfg/
```

##### Launch options : 
```
$ -high -console -novid +exec autoexec.cfg
```

##### Recommended / useful commands :
> These commands were originally intended to optimize CSGO performance on Linux, by forcing the use of libraries installed on the workstation.\
> I don't know if there is still any interest with these commands since 2017, and especially with CS2.

```
$ find ~/.steam/root/ \( -name "libgcc_s.so" -o -name "libstdc++.so" -o -name "libxcb.so*" \) -print -delete
$ sudo apt-get install linux-tools && sudo apt-get install linux-cpupower 
$ sudo cpupower frequency-set -g performance
```
