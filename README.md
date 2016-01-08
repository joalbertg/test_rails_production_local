# Dksh-Rails-Base

> **Note:** This repository contains the core code of Dksh-Rails-Base

## How to use

Make sure you have Ruby and Rails installed onto your machine, if you do not have yet please google by: how to install Ruby on Rails will you have a lot of step-by-step how to do it.

After install the Ruby and Rails needs to clone the repository
```
git clone https://github.com/douglas-dksh/dksh-rails-base.git
```
After that access the new directory and run
```
bundle install
```

Now we can start the WEBrick
```
rails server -b
```

After that if you have no problems with the gems, you can access http://localhost:3000

If you want to use another ip address rather than localhost you can pass through the command line the information about the ip address and the port

```
rails server -b 0.0.0.0 -p 3000
```

The parameter -b : Binds Rails to the specified IP
The parameter -p : Runs Rails on the specified port.

If you need the full list of parameters run
```
rails server --help
```

### License

The easy-debian scripts are open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
