# django_reporting_project
A Dashboard with Django, MongoDB, and Pivot Table. The following tools are used:
* <a href="https://www.djangoproject.com/">Django</a> - A Python web framework
* <a href="https://www.mongodb.com/">MongoDB database</a>
* <a href="https://www.flexmonster.com/?r=gt_dj_m">Flexmonster Pivot Table & Charts</a> - a front-end library for data visualization
* <a href="https://www.flexmonster.com/doc/mongodb-connector/?r=gt_dj_m">The MongoDB connector by Flexmonster</a>

To successfully run the project, do the following:

* Download / clone this GitHub sample
* Download the MongoDB connector and set it up by following the instructions from the guide.
* In django_reporting_project/dashboard/templates/your_report.html, specify the name of the MongoDB collection to which to connect from the pivot table.
* Run the MongoDB connector
* Run the Django development server: python manage.py runserver
* Open http://127.0.0.1:8000/report/ and choose the report on the navigation bar.

This project was inspired in the <a href="https://www.freecodecamp.org/news/how-to-build-a-web-based-dashboard-with-django-mongodb-and-pivot-table/">freeCodeCamp</a> tutorial.
