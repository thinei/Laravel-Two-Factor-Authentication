# Laravel-Two-Factor-Authentication

### Step by Step Implementation

- Clone the repository with git clone
- Copy .env.example file to .env and edit database credentials there, also email provider settings (to send verification codes)
- composer install
- php artisan key:generate
- php artisan migrate --seed (it has some seeded data for your testing)
- php artisan serve

   You can login to adminpanel with default credentials 
     - Username 　➔  admin@admin.com
     - Password 　➔  password
     
 
 ### MailTrap Setting
 ```
MAIL_DRIVER=smtp
MAIL_HOST= smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=[MailtrapのUsername]
MAIL_PASSWORD=[MailtrapのPassword]
MAIL_ENCRYPTION=null
 ```
