
# Classroom Dashboard

Classroom Dashboard is a tool to facilitate student engagement during class and lecture. A student and a professor use the tool in different ways to foster participation, familiarity between student-professor relationships, and help build student-student relationships as well. 

This tool takes advantage of the technology that is often brought into lectures: smart phones and laptops. The functionality includes features such as equity cards to promote student participation and quizzes to promote engagement and attendance. Classroom Dashboard bridges the gap between the surrounding abundance of technology and the manner in which the course material is absorbed by organizing these interactions.

## Architecture

### Prerequisites

TODO: List what a user needs to have installed before running the installation instructions below (e.g., git, which versions of Ruby/Rails)
Rails 5

### Gems
Include the gem in your Gemfile:
```
gem 'paperclip', '~> 6.0'
```

gem 'image_magick', '~> 0.1.9'

Install: gem install paperclip gem install image_magick
bundle install
TODO: List which gems you added to the project, and the purpose each gem serves in your app.

## Installation

TODO: Describe the installation process (making sure you mention `bundle install`).
Instructions need to be such that a user can just copy/paste the commands to get things set up and running. 

## Functionality

TODO: Write usage instructions. Structuring it as a walkthrough can help structure this section,
and showcase your features.

### Add Section

  Add a new section with name (ex: 'CS5') and semester (ex: 'S2018') parameters. 

#### Student List

Display all students within a class, each as a link to a personal student page containing all information. 

##### Add Student

Add a new student with image, name, pronoun, school, and other parameters. 

##### Update / Delete Student

From the Student List page, click on a student to update or delete. 

#### Random Student

Generates random student for cold-calling purposes. The generated student links to student's personal page. 

## Known Problems

TODO: Describe any known issues, bugs, odd behaviors or code smells. 
Provide steps to reproduce the problem / name a file or a function where the problem lives.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D









