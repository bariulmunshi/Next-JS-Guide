# Table of Content
- [hooks: useRouter, useParams and useSearchParams](#hooks-userouter-useparams-and-usesearchparams)
  - [useSearchParams](#usesearchparams)
  - [useRouter](#userouter)
  - [useParams](#useparams)
- [React Component](#react-component)
  - [Server component](#server-component)
- [Should You Use Redux in Next.js?](https://javascript.plainenglish.io/should-you-use-redux-in-next-js-5e57201c34da)
- [Import Alias](#import-alias)
- [Hydration](#hydration)
- [Next JS Rendering](#next-js-rendering)
  - [pre rendering](#pre-rendering)
  - [client side rendering](#client-side-rendering)
- [Next.JS Basic Understand](#nextjs-basic-understand)

# hooks: useRouter, useParams and useSearchParams
## useParams
-  
## useSearchParams
-  
## useRouter
- Method(push,replace,back,forward)



# React Component
## Server component
- In NEXT.js-13 app router folder by default component will be server component. we connect with database. 
- Advantages: 
## client component

# Import Alias
- An alias is a way to create shortcuts for your imports.
- "@/*": ["./src/*"] or @/* = ./src/*


# Hydration
- In server side rendering all html contents come from the server. Then needs to interactivities in the client. The process of add interactivities like event listeners, add javascript animations etc. it's called hydration.


# Next JS Rendering 
## Pre Rendering
   - Static Site Generation(SSG)
   - `Server Side Rendering`
      ```sh
      1. Generate HTML in request time 
      2. Website all content found in HTML file
      3. It has dynamic data comes from database
      4. Generate HTML Files in the server every single request time. 
      ```
   - Incremental Static Regeneration
## Client Side Rendering
   ```sh
    1. Traditional react single page app(using vite)
    2. A html block a lot of JavaScript codes come from the server side.
    3. All HTML content Generate in the client(browser) using JavaScript.
    4. It's not suitable for SEO.
   ```
# Next.JS Basic Understand
- We can write CSS in global.css file
- Next.JS has built in font