Themosis Example
==================


The following is a themosis framework example.

build
-------
composer install

setup
-------
duplicate the .env.local to .env and set the database credentials and site URL
run the URL and setup WordPress
create dummy data (post categories and posts)


API Endpoints
-------
/api/v1/categories : seeds all current categories
/api/v1/posts/{cat_id} : seeds posts for a given category id

Frontend example
-------
/example
the frontend code retrieves the categories from the API endpoint and dynamically loads posts on swipe.



License
-------
The Themosis framework is open-source software licensed under [GPL-2+ license](http://www.gnu.org/licenses/gpl-2.0.html).
