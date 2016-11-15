![Sinatra from scratch](https://guides.nanobox.io/assets/quickstart-icons/sinatra.png)

#### Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-sinatra.git

# cd into the sinatra app
cd nanobox-sinatra
```

#### Run the app

```bash
# Run sinatra as you would normally, with Nanobox
nanobox run ruby myapp.rb
```

#### Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local sinatra.dev
```

Visit your app -> [sinatra.dev:3000](http://sinatra.dev:3000)

#### Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where ruby is installed,
ruby -v

# your gems are available,
gem list

# and your code is mounted
ls
```

#### Now What?
For more details about running sinatra apps with nanobox visit [guides.nanobox.io/ruby/sinatra/](https://guides.nanobox.io/ruby/sinatra/)
