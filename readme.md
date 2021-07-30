### go
https://github.com/golang/go

#### SettingGOPATH

https://github.com/golang/go/wiki/SettingGOPATH

###### GOPATH can be any directory on your system. In Unix examples, we will set it to ###### \$HOME/go (the default since Go 1.8). Note that GOPATH must not be the same path as your Go installation. Another common setup is to set GOPATH=$HOME.



##### Edit your ~/.bash_profile to add the following line:
```bash
export ANDROID_SDK_ROOT= ~/Library/Android/sdk
export NDK_ROOT=$ANDROID_SDK_ROOT/ndk/19.2.5345600

export ANDROID_HOME=$ANDROID_SDK_ROOT

export GOPATH=$HOME/go

export PATH=${PATH}:${ANDROID_SDK_ROOT}\tools:${ANDROID_SDK_ROOT}\platform-tools:${NDK_ROOT}:$GOPATH/bin
```


Save and exit your editor. Then, source your ~/.zshrc.

```bash
source ~/.bash_profile
```

<br>

### gomobile
https://github.com/golang/mobile

#### Gomobile is a tool for building and running mobile apps written in Go.
https://pkg.go.dev/golang.org/x/mobile/cmd/gomobile

To install:

```bash
$ go get golang.org/x/mobile/cmd/gomobile
$ gomobile init
```

