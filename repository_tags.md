# Capstone Repository Tags and Branches

To checkout a specific branch

```shell
git clone https://github.com/jhu-ep-coursera/capstone_demoapp.git (dirname) --branch (branch-or-tag-name)
```

To checkout a specific tag

```shell
git clone https://github.com/jhu-ep-coursera/capstone_demoapp.git (dirname)
cd (dirname)
git checkout tags/(tagname) -b (any-branch-you-want-to-call-it)
```

Examples:

* Cloning the repository and checking out the `asset-pipline` branch into the `asset-pipeline` directory

```
$ git clone https://github.com/jhu-ep-coursera/capstone_demoapp.git asset-pipeline --branch asset-pipeline
```

* Cloning the repository into the spa-app directory and checking out the `spa-app.start` tag into the `spa-app` branch

```shell
$ git clone https://github.com/jhu-ep-coursera/capstone_demoapp.git spa-app
$ cd spa-app
$ git checkout tags/spa-app.start -b spa-app
Switched to a new branch 'spa-app'
```


## Module 1

* **app-setup.start** - blank repository, start of course
* **ex-rqmts.starti** - readying for RSpec
* **rdbms-api.start** - readying for RDBMS Resource
* **mongodb-api.start** - readying for MongoDB Resource
* **deployment.start** - readying for deployment

## Module 2

* **module2.start**
* branch: **asset-pipeline** - Asset Pipeline setup
* branch: **gulp** - External development setup
* branch: **external-rails** - External dev deployed to Rails
* **spa-app.start** - ready to add basic SPA application
* branch: foos-ui - Rails/Angular application

## Module 3

* **module3.start**
* branch: rspec
* branch: rspec-mongoid
* branch: db-cleaner
* branch: factorygirl
* branch: api-specs
* branch: ui-specs
* **testing-assignment** - commit to use for assignment

## Module 4

## Module 5

## Module 6

## Module 7

## Module 8
