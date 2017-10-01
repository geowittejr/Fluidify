# Project Documentation


### CSS Modules

I looked into doing inline styles in React and decided against it. I like the idea of keeping the styling
separate from code. It also seems that it would make it easier to move away from React without having to
redo all the styles.  CSS Modules appear to be a good solution.

https://javascriptplayground.com/blog/2016/07/css-modules-webpack-react/
https://github.com/css-modules/css-modules


### React and TypeScript

This is a good project template:
https://github.com/rangle/typescript-react-redux-starter

This blog post explains the setup involved with React, TypeScript, and Webpack:
http://blog.tomduncalf.com/posts/setting-up-typescript-and-react/#recommendation


### Automatically Deploy

http://cloudcannon.com/tutorial/2016/01/21/deploy-jekyll-sites-to-s3-using-travis-ci/

https://docs.travis-ci.com/user/deployment/lambda

https://travis-ci.org/geowittejr/Audeeo/settings

http://bytes.babbel.com/en/articles/2016-05-20-deploy-lambda-functions-using-travis.html


### App Features
- Assign tasks a context such as:
  - @Home
  - @Computer
  - @Errands
- Assign a category to tasks or projects to show which tasks are related to a particular category of life such as:
  - Employee
  - Husband
  - Father
  - Author
  - Programmer
