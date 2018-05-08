# thoughtLogger
software to log ideas

UI spec:
  text box for entry of text blob (idea to be logged)
  2nd text box for tags
    as tagged are applied the text box is emptied
    autocomplete using existing tag values (can the query identify which tags exist using mongo???)
    new text input creates new tag

logging spec:
  text is logged in db
  meta tags are applied
    values submitted via ui are contained in array (do i go relational or mongo???)
    date of submission time
    geo location extracted? (only relevant for mobile case really, but i think this would require it be an app)

reading spec:
  search by tags
  maybe do graph representation?
 
search by text body but will likely be simple in design

