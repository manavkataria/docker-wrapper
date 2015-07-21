# docker-wrapper
Wrapper Script for GIT + Docker Development on Mac OS X

## Functionality
```
Usage: ./docvm [options]
    NO_OPTION    Setup linc environment in current directory <repo.git>
    help         Display this usage information
    kill         Stop and remove 'dev' container
    run          Run linc's django server
    shell        Open interactive shell on 'dev' container
    bashinit     Setup ~/.bash_profile to enable docker commands
    uninstall    Uninstall 'boot2docker' and 'docker'
    version      Display script version
```

## Getting Started

1. **Download**: [_.docvm-config_](https://github.com/manavkataria/docker-wrapper/blob/master/sample.docvm-config) and save-as `~/.docvm-config`
2. **Download**: [_docvm_](https://github.com/manavkataria/docker-wrapper/blob/master/docvm) and save-as `/usr/local/bin/docvm` 
3. **Mark as Executable**: chmod +x `/usr/local/bin/docvm`
4. **Execute**: _docvm_ in a **new directory** where you want to setup the dev environment
