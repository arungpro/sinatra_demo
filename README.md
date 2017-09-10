# Sinatra Demo
Wow!!! Do you know how easy it is to create a web app.

Sinatra is a URL to method mapper. Which is extremely lightweight and
easy to use gem for ruby.

let me walk you through in here,

## Requirement
  * Programming Language
    - [Ruby](https://www.ruby-lang.org/en/downloads/)
  * Server
    - [puma](https://github.com/puma/puma)
  * Router
    - [Sinatra](https://github.com/sinatra/sinatra)
    
## Usage
    1. Clone sinatra_demo repo
      - [sintra demo](git@github.com:arungpro/sinatra_demo.git)
    2. get into the repo and run ruby file
      - ruby sinatra_demo.rb
      
      See below for reference
      ![Output]()

    3. From any browser, try loading http://localhost:4567/
      what you see in browser
      ![Output]()
      you will see the request hits in terminal
      ![Output]()
    
    
## Routes
   In Sinatra, a route is an HTTP method paired with a URL-matching pattern. Each route is associated with a block:
   
    get '/' do
      .. show something ..
    end

    post '/' do
      .. create something ..
    end

    put '/' do
      .. replace something ..
    end

    patch '/' do
      .. modify something ..
    end

    delete '/' do
      .. annihilate something ..
    end

    options '/' do
      .. appease something ..
    end

    link '/' do
      .. affiliate something ..
    end

    unlink '/' do
      .. separate something ..
    end
    
 ## Reference
 [Sintara Documentation](https://github.com/sinatra/sinatra)
    
