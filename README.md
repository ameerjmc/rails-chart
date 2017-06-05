# README

### Create beautiful Javascript charts with one line of Ruby on Rails

include the gem in your Gemfile:

<body>

    gem 'chartkick'
    
</body>


And then execute:


<body>


   $ bundle install
   
   
</body>


Steps:

1.rails g model student

2.rake db:migrate

3.rails g controller students index


## index.html.erb


<body>

	<%= pie_chart Student.group(:course).count %>
	
	<%= column_chart  Student.group(:course).count %>
	
	
</body>

### pie-chart

![Alt text](https://github.com/ameerjmc/rails-chart/blob/master/public/pie_chart.png "pie_chart")

### column-chart

![Alt text](https://github.com/ameerjmc/rails-chart/blob/master/public/column_chart.png "column_chart")


	





