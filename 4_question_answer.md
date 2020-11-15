1. This is an explanation of how to use "singular" and "plural" properly in Rails.

**For example, "blogs" is specified for parameters when creating a controller, and "blog" is specified for parameters when creating a model. It seems that various variables are automatically created based on that, so I think it makes sense to use "blogs" and "blog" properly, but it is still confusing because there is no description anywhere.**  

Thank you for trying to make it understandable, but I would like to clarfy a little bit and it never make you confused again.
Here it is Database tables use student. Table names are plural.=> this will be students as Table name.
But Column names in the database use student, but are generally singular.

Eg:
+--------------------------+
| bigfoot_sightings        |
+------------+-------------+
| id         | ID          |
| sighted_at | DATETIME    |
| location   | STRING      |
| profile_id | FOREIGN KEY |
+------------+-------------+

+------------------------------+
| profiles                     |
+---------------------+--------+
| id                  | ID     |
| name                | STRING |
| years_of_experience | INT    |
+---------------------+--------+

Model class names use CamelCase. These are singular, and will map automatically to the plural database table name.Model attributes and methods use student and match the column names in the database.Model files go in app/models/#{singular_model_name}.rb

Eg:
# app/models/bigfoot_sighting.rb
class DiveintoCode < ActiveRecord::Base
  # This class will have these attributes: id, sighted_at, location
  def veteran_hunter?
    years_of_experience > 2
  end
  # Methods follow the same conventions as attributes
end

Controller class names use CamelCase and have Controller as a suffix. The Controller suffix is always singular. The name of the resource is usually plural.
DiveintoCodesController < ApplicationController
  `def index`
    # ...
  `end`
  `def show`
    # ...
  `end`
  # etc
end
Route names are student, and usually match the controller. Most of the time routes are plural and use the plural resources.
route.rb
resources :diveintocodes

Views
View file names, by default, match the controller and action that they are tied to.

Views go in app/views/#{resource_name}/#{action_name}.html.erb.

Examples:

app/views/diveintodes/index.html.erb


1. Even if I try "rake routes", there are "blog" "new_blog" "blogs" and "confirm_blogs" in Prefix. I don't understand why this is happening at all.

Thank you for asking, now we are going to look together how Rails routing configurations are kept in config/routes.rb file. And Taking parameters depends on many things. rake routes will show with routes take parameters. Member actions will take parameters.
## Routing 
*The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.*
 When your Rails application receives an incoming request for:
`GET /blogs/new`
it asks the router to match it to a controller action. If the first matching route is:

`get '/blogs/:new', to: 'blogs#create'`

and your application contains this code in the controller:

`@blog = Blog.new(params[:blog])`
and this in the corresponding view:
`<%= link_to 'New Blog', blog_path(@blog) %>`



blogs    GET        /blogs(.:format)          blogs#index
         blog       /blogs(.:format)          blogs#create
edit_blog GET       /blogs/:id/edit(.:format) blogs#new

*Hope you've get something, not either feel free to ask again. Once again thank you for your concern.*

