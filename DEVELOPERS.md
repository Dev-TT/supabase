# Developing Supabase

* [Development Setup](##Development-Setup)
* [Installing Dependencies](###Installing-Dependencies)
* [Building Supabase](##Building-Supabase)
* [Start a Development Server](##Start-a-Development-Server)

## Development Setup

This document describes how to set up your development environment to build and test Supabase.

### Installing Dependencies

Before you can build Supabase, you must install and configure the following dependencies on your
machine:

* [Git](http://git-scm.com/)

* [Node.js v16.x (LTS)](http://nodejs.org)

* [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Forking Supabase on Github

To contribute code to Supabase, you must fork the [Supabase Repository](https://github.com/supabase/supabase). After you fork the repository, you may now begin editing the source code.

## Building Supabase

To build Supabase, you clone the source code repository:

2. Clone your Github forked repository:
   ```sh
   git clone https://github.com/<github_username>/supabase.git
   ```

3. Go to the Supabase directory:
   ```sh
   cd supabase
   ```

### Choosing Directory

Before you start a development server, you must choose if you want to work on the [Supabase website](https://supabase.io) or [Supabase Docs](https://supabase.io/docs/).

1. Go to the supabase.io directory
    ```sh
    cd www
    ```
    or Go to the [Supabase Docs](https://supabase.io/docs/) directory
    ```sh
    cd web
    ```

2. Install npm dependencies:

    npm
    ```sh
    npm install
    ```

    or with yarn
    ```sh
    yarn install
    ```

3. Build Project:

    npm
    ```sh
    npm run build
    ```

    or with yarn
    ```sh
    yarn run build
    ```

## Start a Development Server

To debug code, and to see changes in real time, it is often useful to have a local HTTP server.

1. Start development server

    npm
    ```sh
    npm run start
    ```

    or with yarn
    ```sh
    yarn dev
    ```

2. To access the local server, enter the following URL into your web browser:

    [Supabase website](https://supabase.io)
    ```sh
    http://localhost:3000
    ```

    [Supabase Docs](https://supabase.io/docs/)
    ```sh
    http://localhost:3005/docs
    ```
