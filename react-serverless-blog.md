# How to Build a Serverless, SEO-friendly React blog 

Serverless application architectures are gaining in popularity and it's no mystery why. Developers are able to build and iterate on products faster when they have less infrastructure to maintain and don't need to worry about server maintenance, outages, and scaling bottlenecks, 

In this tutorial we are going to show you how to build a serverless, CMS-powered blog using React, ButterCMS, and built-in prerendering through Netlify. The finished code for this tutorial is available on Github.

[ButterCMS](https://buttercms.com) is a hosted API-based CMS and content API that lets you build CMS-powered apps using any programming language including [Ruby](https://buttercms.com/ruby-cms), [Rails](https://buttercms.com/rails-cms), [Node.js](https://buttercms.com/nodejs-cms), [.NET](https://buttercms.com/asp-net-cms), [Python](https://buttercms.com/python-cms), [Phoenix](https://buttercms.com/phoenix-cms), [Django](https://buttercms.com/django-cms), [Flask](https://buttercms.com/flask-cms), [React](https://buttercms.com/react-cms), [Angular](https://buttercms.com/angular-cms), [Go](https://buttercms.com/golang-cms), [PHP](https://buttercms.com/php-cms), [Laravel](https://buttercms.com/laravel-cms), [Elixir](https://buttercms.com/elixir-cms), and [Meteor](https://buttercms.com/meteor-cms). Butter lets you manage content using our dashboard and integrate it into your front-end of choice with our API – you can think of Butter as similar to WordPress except that you build your website in your language of choice and then plug-in the dynamic content using an API.

[Netlify](https://netlify.com) is a static website hosting service that handles integration with prerenering services like Prerender.io, SEO.js, and Brombone.

### Getting Started

We'll use the [Create React App](https://github.com/facebookincubator/create-react-app) starter kit.

Install Create React App:
```
npm install -g create-react-app
```

Then create the boilerplate for our app:

```
create-react-app react-serverless-blog
cd react-serverless-blog
npm start
```

### Building the blog

Next we’ll use [ButterCMS](https://buttercms.com) to build our blog. ButterCMS provides [content APIs](https://buttercms.com/docs/api) for blog posts, categories, tags, and authors.

First we'll install the [ButterCMS Node.js API client](https://github.com/buttercms/buttercms-node):

```
npm install buttercms --save
```

We'll create two components – one for listing all posts and another for displaying individual posts.




### Prerendering



## Wrap Up


