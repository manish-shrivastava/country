# country.sql
It is a [country list sql](https://github.com/manish-shrivastava/country.sql/blob/master/country.sql). Just **Copy Paste Go** sql file to create countries table with all contry insert into database.

The Imported SQL contains the following info:

#####Table name:  `countries`
##### Fields: 

* `id`: Primary key

* `country_code`: Two digit Country Short code (i.e. IN for INDIA)

* `name`: Full name of the Country.


# For Ruby on Rails
If you want to create `countries` table with all country data in ruby on rails. then you will have to create a model using below command.

    rails g model Country country_code:string name:string

after that you will be able to use [this seed file](https://github.com/manish-shrivastava/country.sql/blob/master/rails_country_seed_data.rb) to copy it to your project's `db/seed.rb` and import it via:

    rake db:seed


Please let me know if you have any doubt.

#contact

Manish Shrivastava

Mob: +91-9993858772

Email: er.manishshrivastava@gmail.com

URL: http://www.manishshrivastava.com
