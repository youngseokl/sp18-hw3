## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
  It is the value of course_name that the user enters. If the user doesn't enter any, value gets set to the placeholder value.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
  routes.rb has a post action to the address, and this means that we are sending our data.

3. What type of request did your browser just perform?
  post

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
  localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
  We have sent our information such as full_name and course that shows up on the address.
