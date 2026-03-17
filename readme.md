# ruby-project-template

This is a boilerplate template for quickly jump-starting a simple Ruby project. It provides a basic structure and setup to help you get started with your Ruby application development.

## Features

- Organized project structure
- Pre-configured `bin/app` entry point
- Example `lib/app.rb` module
- Dependency management with Bundler
- Licensed under the Mozilla Public License, v. 2.0

## Getting Started

1. **Clone the Repository**  
   Clone this template to your local machine:
```bash
git clone https://github.com/kelvinchincc/ruby-project-template.git your-project-name
cd your-project-name
```

2. **Install Dependencies**  
   Install the required gems using Bundler:
```bash
bundle install
```

3. **Run the Application**  
   Execute the default application:
```bash
ruby bin/app
```

   You should see the message: `Hello, World!`

4. **Customize the Application**  
   - Modify `bin/app` to suit your needs. You can rename this file to your desired entry point.
   - Update `lib/app.rb` with your application logic.

## Project Structure

```
ruby-project-template/
├── bin/
│   └── app          # Entry point for the application
├── lib/
│   └── app.rb       # Core application logic
├── Gemfile          # Gem dependencies
├── Rakefile         # Rake tasks
├── license.md       # License information
└── readme.md        # Project documentation
```

## License

This project is licensed under the Mozilla Public License, v. 2.0. See [license.md](license.md) for details.
