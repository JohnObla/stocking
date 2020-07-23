# README

Created this project to learn Ruby on Rails.
By John Obla

Below is a documentation of my learning process.

Decided I wanted to learn Ruby

Found a nice looking rails course with projects

Course recommened I have an understanding of Ruby

Completed intro to beginners course, to learn Ruby syntax

Continued with original Ruby course

Ruby course recommended I use an online code editor for ruby (cloud 9 or codeanywhere)

    I decided against this as I'd miss out on a huge learning experience if I used a pre-packaged IDE

Begans setting up Ruby and Rails on my windows machine

Kept consistently running into different errors

Every error I troubleshooted (troubleshot?) in stack overflow recommended not to use Windows for Ruby on Rails development

    Main reasons were due to Windows binaries conflicting with the Ruby/Rails code

Decided to use Linux for my IDE setup (no previous experience with Linux)

Downloaded the Linux Ubuntu ISO file from their official website and span up a virtual machine using Virtual Box

Continued Ruby on Rails setup with my Ubuntu VM

Ran into an issue where the saasc bundle gem entry would stall while attempting to bundle

Searched the internet and found an open bug for this issue on saasc's github repo

Found my own workaround by running Rails 5 instead of Rails 6

    Commented my workaround on the github bug page: https://github.com/sass/sassc-ruby/issues/209

Successfuly created my first Rails projects

Learned how Ruby + Rails handles the MVC framework

Bug author for sassc bug solved his own issue by increasing the ram on his linux virtual machine

    Sadly I couldn't use his solution as I don't have enough ram to allocate

    I carried on using my workaround

Learned about ActiveRecord basics and how it interacts with classes and models

Due to slow nature of my ruby course, found another that emphasises project creation

Discovered RailsInstaller.org and switched back to windows after recurring sassc bug

Fixed a problem with sqlite3 fetching the wrong version in the gemfile

Bootstrap refuses to import, found out I didn't include the gem entry for bootstrap!

STILL GETTING SASSC issue

Solved sassc issue by downgrading to version 2.1.0!!!

Installed bootstrap on the back of this!

Latest push to GitHub flagged security issues, couldn't fix as they require the latest version of Rails

    An older rails version must be used as it's what comes with the railinstaller.exe

Taught myself error handling using 'rescue' as the api version I'm using throws an error instead of returning null

Also handled a NoMethod error as the api is flaky with how it handles incorrect symbols

Learnt more about Rails database abstraction

Got user authentication working

Pausing this lecture to start with testing + TDD
