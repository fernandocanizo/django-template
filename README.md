# Django Template

A wannabe starter template for new Django projects.


# How to use it

```
git clone https://github.com/fernandocanizo/piopio.git
git rename origin django-template
git remote add origin https://github.com/fernandocanizo/my-new-shiny-new-project.git
# rename the project
egrep -rl django_template | sed -i 's/django_template/my-new-shiny-new-project/g'
git commit -a -m "Start project my-new-shiny-new-project"
git push -u origin master
```
