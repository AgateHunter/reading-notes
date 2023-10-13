# Lesson 03 - Revisions and the Cloud

## Git it? Got it? Good!

### Version Control

Version Control can be broken down into three categories:
* Local Version Control
* Centralized Version Control
* Distributed Version Control

#### Local Version Control

This allows you to make changes to the files on a computer's hard disk

#### Centralized Version Control

When the need for multiple developers to collaborate on one or multiple files, the Centralized Version Control System (CVCS) was created.
A CVCS means that multiple people can make changes on file(s). 

#### Distributed Version Control

The flaw with a CVCS is that everything lives on just one database; if that goes down, no one can work. A Distributed Version Contrl system allows
many miorred repositotires, so people can work as a team and things aren't all stored in just one location

## Did you GIT it yet?

*Git* is a snapshot of your project; the file that is being worked on is saved exactly as it in at that moment in time. The save is called a ***commit***
When you **clone** in Git, you make a copy of the repository on your *local machine*

## A - C - P ... Repeat!

1. **Add** - git add . allows you to track files in a respository
2. **Commit** - git commit -m -" " Once you've made changges to your fine, you should commit the changes. It's important to make note of what you changed in the message " "
3. **Push** - git push origin master - This is what you need to do to make sure the changes are made in the primary repository. That way, everyone can see the *latest* version.
