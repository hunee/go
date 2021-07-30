https://github.com/golang/go
https://github.com/golang/mobile

#### SettingGOPATH

https://github.com/golang/go/wiki/SettingGOPATH

###### GOPATH can be any directory on your system. In Unix examples, we will set it to ###### \$HOME/go (the default since Go 1.8). Note that GOPATH must not be the same path as your Go installation. Another common setup is to set GOPATH=$HOME.



##### Edit your ~/.bash_profile to add the following line:
```bash
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
```


Save and exit your editor. Then, source your ~/.zshrc.

```bash
source ~/.bash_profile
```

<br>

#### Gomobile is a tool for building and running mobile apps written in Go.
https://pkg.go.dev/golang.org/x/mobile/cmd/gomobile

To install:

```bash
$ go get golang.org/x/mobile/cmd/gomobile
$ gomobile init
```

