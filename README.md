# Get That Job

## App

Get that job is a Sinatra application.

Sinatra is a library to create web applications with Ruby. We'll learn
more about it during the next module.

What you need to know now is tat, sinatra is configured to convert any `.erb` 
file that you add to the `views` folder into page of the application

### ERB

ERB is a template language for Ruby. You will learn more about it in the future
but for this project you are going to use 2 of it's main features.

- [Layout](https://share.getcloudapp.com/qGuoXqAL)
  - The idea with this is that you can add to the Layout the elements
    that are repeated in all the pages, like the navbar and the footer.
- [Includes](https://share.getcloudapp.com/Qwu79y5E).
  - You can use includes to reuse pieces of UI in several places! Remember,
    if you are repeating the exact same html + css, you probably should
    be using an include!

### Creating a new page

To create a new page for the site, simply create a `.erb` file in the views
folder.

The name of the file will be the same as the url of the new page.

For example, if you create a file with the name `jobs`, the content
of the file will be displayed when you go to [/jobs](http://localhost:4567/jobs)

[Explaining Video](https://share.getcloudapp.com/WnuNBWZg)

### Installation

To install the application dependencies, run `bundle install`.
If bundle is not updated it will prompt you to run `bundle update --bundler`, if so, 
run that command and then rerun `bundle install`

### Running the app

You can start the app with `ruby app.rb`

You can see the app if you go to [http://localhost:4567/](http://localhost:4567/)

### Adding assets

[Explanation](https://share.getcloudapp.com/YEuAXYjO)

### Resources

- [Design](https://www.figma.com/file/LAdYG5wMqFFpCYLlZGEHCf/Get-That-Job-Gate-Evaluation?node-id=4%3A20919)
- [Stories](./stories.md)
- [Trello Board with Stories](https://trello.com/b/VJanzZmR/get-that-job)

**Good luck!**
