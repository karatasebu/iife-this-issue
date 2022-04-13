## Installation

```
https://github.com/karatasebu/iife-this-issue
cd iife-this-issue
npm install
```

## For Error

```
npm run build
npm run preview
```
Open the browser console

## Description

There is no issue in dev environment but in production when using "this" as parameter in iife, "this" should mean window object but transpiled another variable. I am using device-uuid package and this package using iife with "this" parameter for example.