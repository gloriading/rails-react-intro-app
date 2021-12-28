# README

Learning source: https://blog.logrocket.com/how-to-use-react-ruby-on-rails/

1. `rails new rails-react-todo --webpack=react`
2. `rails g controller todos index`
3. in config/routes.rb

   ```rb
       root 'todos#index'
   ```

4. in app/view/layouts/application.html.erb, before closing head tag:

   ```html
   <% javascript_pack_tag 'hello_react %>
   ```
