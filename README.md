
## The RxJs In Practice Course

This repository contains the code of the [RxJs In Practice Course](https://angular-university.io/course/rxjs-course).

This course repository is updated to Angular v10, and there is a  package-lock.json file available, for avoiding semantic versioning installation issues.

![RxJs In Practice Course](https://s3-us-west-1.amazonaws.com/angular-university/course-images/rxjs-in-practice-course.png)


# How To install this repository

We can install the master branch using the following commands:

    git clone https://github.com/angular-university/rxjs-course.git
    
This repository is made of several separate npm modules, that are installable separately. For example, to run the au-input module, we can do the following:
    
    cd rxjs-course
    npm install

Its also possible to install the modules as usual using npm:

    npm install 

NPM 5 or above has the big advantage that if you use it you will be installing the exact same dependencies than I installed in my machine, so you wont run into issues caused by semantic versioning updates.

This should take a couple of minutes. If there are issues, please post the complete error message in the Questions section of the course.

# To Run the Development Backend Server

In order to be able to provide realistic examples, we will need in our playground a small REST API backend server. We can start the sample application backend with the following command:

    npm run server

This is a small Node REST API server.

# To run the Development UI Server

To run the frontend part of our code, we will use the Angular CLI:

    npm start 

The application is visible at port 4200: [http://localhost:4200](http://localhost:4200)



# Important 

This repository has multiple branches, have a look at the beginning of each section to see the name of the branch.

For operators, use https://github.com/bxh/rxjs-courses/tree/1-operators-finished branch.

For subjects and store, use https://github.com/bxh/rxjs-courses/tree/2-store-finished branch.
