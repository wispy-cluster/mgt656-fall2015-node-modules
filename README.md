# Node modules for the class project

On cloud9, our virtual machines have very little memory and this causes
our `npm install` command to fail. Here, we've made a repository of the
`node_modules` directory so that you don't have to install them yourself,
you can just grab this.

To install, log into your cloud9 workspace for the class project,
then remove whatever node_modules directory you have already

    rm -rf node_modules
    
Then, clone this repository

    git clone git@github.com:yale-mgt-656/mgt656-fall2015-node-modules.git node_modules
    
Then, you're done. You should be able to run the app on cloud9.

