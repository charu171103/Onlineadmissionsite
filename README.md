# Onlineadmissionsite
This Django web app implements user authentication, directing new visitors to the login page. New users can register via the "Signup" link, while existing users log in. Upon successful login, users access the home page with links to "About" and "Apply."

Home Page: Users initially encounter the login page. After login, they land on the home page with navigation to "About" (college info) and "Apply" (course application).

Login Page: Users input login credentials (username, password). Successful authentication leads to the home page.

Signup Page: New users register by providing essential details (username, email, password) and are directed to the home page post-registration.

About Page: Offers detailed college information, including history and mission.

Apply Page: Lists available courses for users to apply, requiring relevant details for course enrollment.

Logout Functionality: Users can log out from any page, returning them to the login page.

*Implementation*:

Django Authentication: Utilizes Django's authentication for user management.
Views & Templates: Develops views for pages and corresponding HTML templates.
Navigation: Links are established within templates for seamless page switching.
Security: Protects authenticated views using Django's @login_required.
Course Application: Implements a form for users to apply for courses on the "Apply" page.
