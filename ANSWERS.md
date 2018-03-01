## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
  It represents the initial value that is in the form.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
  There is no route that matches.

3. What type of request did your browser just perform?
  It performed a get request.

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
  http://localhost:300/teachers

5. Why does `localhost:3000/teachers` work now?
  It works because submitting the form is a post request and we have a route for that.
