# README

## Introduction

Active Admin is a Ruby on Rails plugin for generating administration style interfaces.

## Installation
Add this in your gemfile

```
gem 'activeadmin' 
gem 'inherited_resources' , github: 'activeadmin/inherited_resources'
gem 'devise'
```

## Create models

```
rails g scaffold User
rails g scaffold Post User:reference
```

```
rake db:seed
rake db:migrate
```

## Access

```
/admin/login
```

