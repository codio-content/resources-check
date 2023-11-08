# Optimization for node_modules

NodeJs software often requires external modules installed either by `yarn` or `npm`, some dependencies can be very big and take a lot of space.

To speed up assignment creation and reduce the size of the assignment, you can use `.assignmentignore` file to exclude `node_modules` folder from the assignment. In this case your learners would need to run `yarn` or `npm install` to install all dependencies.

Installing dependencies will require additional time, but it will be done only once and will not affect the performance of the assignment. 

We would recommend to cache the dependencies in the stack for big simultaneous user cohorts to avoid downloading the same dependencies multiple times from GitHub or npmjs.com.

That can be achieved by running `npm install` or `yarn` install and making a stack version after, that should cache the dependencies according to the lock file in `~/.npm/` folder.
