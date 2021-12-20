# CNC-milling
## Intorduction
This work is mainly about the implement of the methods 
of tool path planing in CNC milling project

The UI framework uses the "Surface Mesh Framework "
of Associate Professor  Xiaoming Fu, University of Science and Technology 
of China.[Frame link](http://staff.ustc.edu.cn/~fuxm/code/index.html#sec_surface_framework)



## Features

* Supported controllers
* [Desktop App for Linux, Mac OS X, and Windows](https://github.com/cncjs/cncjs/wiki/Desktop-App)
* 6-axis digital readout (DRO)
* Tool path 3D visualization



## Getting Started

### Installation

Node.js 8 or higher is recommended.
```
git clone https://github.com/creationix/nvm.git ~/.nvm
cd ~/.nvm
git checkout `git describe --abbrev=0 --tags`
cd ..
. ~/.nvm/nvm.sh
```

Add these lines to your `~/.bash_profile`, `~/.bashrc`, or `~/.profile` file to have it automatically sourced upon login: 
```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```

Once installed, you can select Node.js versions with:
```
nvm install 10
nvm use 10
```

It's also recommended that you upgrade npm to the latest version. To upgrade, run:
```
npm install npm@latest -g
```


### Upgrade

Run `npm install -g cncjs@latest` to install the latest version. To determine the version, use `cncjs -V`.


### Configuration File

The configuration file <b>.cncrc</b> contains settings that are equivalent to the cncjs command-line options. The configuration file is stored in user's home directory. To find out the actual location of the home directory, do the following:

* Linux/Mac
  ```sh
  echo $HOME
  ```

* Windows
  ```sh
  echo %USERPROFILE%
  ```

Check out an example configuration file [here](https://github.com/cncjs/cncjs/blob/master/examples/.cncrc).

### File Format



## Documentation

https://cnc.js.org/docs/

## Examples



## Contributions

Use [GitHub issues](https://github.com/cncjs/cncjs/issues) for requests.

Pull requests welcome! Learn how to [contribute](CONTRIBUTING.md).

## Localization


## Donate


## Contributors

This project exists thanks to all the people who contribute.

## License

Licensed under the [MIT License](https://raw.githubusercontent.com/cncjs/cncjs/master/LICENSE).