# ruby-project-template

This is a boilerplate template for quickly jump-starting a simple Ruby project. It provides a basic structure and setup to help you get started with your Ruby application development.

## Features

- Organized project structure
- Pre-configured `bin/app` entry point
- Example `lib/app.rb` module
- Dependency management with Bundler
- Licensed under the MIT License

## Getting Started

1. **Clone the Repository**  
   Clone this template to your local machine:
   ```bash
   git clone --depth 1 https://github.com/kelvinchincc/ruby-project-template.git your-project-name
   cd your-project-name
   ```

2. **Clean Up the Template**  
   - Remove the `.git` folder to detach the project from the template's version control:
     ```bash
     rm -rf .git
     ```
   - Remove or replace the `license.md` file with your project's license.
   - Remove or replace the `readme.md` file with documentation specific to your project.

3. **Install Dependencies**  
   Install the required gems using Bundler:
   ```bash
   bundle install
   ```

4. **Update `.gitignore`**  
   The `.gitignore` file includes entries specific to the template. Ensure it meets your project's needs. For example:
   - Remove `Gemfile.lock` and `rbs_collection.lock.yaml` entries if you want to commit them to version control.

5. **Run the Application**  
   Execute the default application:
   ```bash
   ruby bin/app
   ```

   You should see the message: `Hello, World!`

6. **Customize the Application**  
   - Modify `bin/app` to suit your needs. You can rename this file to your desired entry point.
   - Update `lib/app.rb` with your application logic.

## Project Structure

```
ruby-project-template/
├── .bundle/
│   └── config       # Bundler configuration
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

This project is licensed under the MIT License. See [license.md](license.md) for details.
