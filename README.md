# README

### Create beautiful Javascript charts with one line of Ruby

### Installation

include the gem in your Gemfile:

gem 'chartkick'

And then execute:

$ bundle install

Steps:

1.rake db:create
2.rails g model student
3.rake db:migrate
4.rails g controller students index


index.html.erb

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	
	<%= pie_chart Student.group(:course).count %>
	<%= column_chart  Student.group(:course).count %>
	
</body>
</html>





