# Order Managemenent System Full-Stack Application Project

## Demo Video Link

*Video compressed due to my monitor resolution*
https://drive.google.com/file/d/1KcRWOb467ygTFy83U_hAJJqlR2wUW41t/view?usp=sharing

## Hardcoded Credentials
Make sure to run the seeder to populate your database with the new user and admin. Use the following command:
```bash
php artisan db:seed
```

Admin account:
- username: admin1@example.com
- password: password

Customer  account:
- username: user1@example.com
- password: password


## Project Overview

The Order Management System is a full-stack application built with Angular, Laravel and MySQL. It serves as the foundation for managing user orders, providing a seamless experience for both regular users and administrators. The application supports user authentication, order creation, and tracking, ensuring that users can easily manage their orders while allowing admins to oversee the entire order management process.

### Potential Future Features

All the bonus points are implemented but there are some features that will improve the project.

As the project evolves, several features could enhance its functionality and user experience:
- Enhanced User Profiles: Allow users to manage their profiles, including updating personal information and viewing order history.
- Payment Integration: Implement payment gateways (e.g., Stripe, PayPal) to facilitate online payments for orders. (Currently Mock)
- Order Notifications: Send email or SMS notifications to users regarding order status updates and confirmations.
- Admin Dashboard: Create a comprehensive dashboard for admins to manage users, view analytics, and track order performance.
- Product Reviews and Ratings: Enable users to leave reviews and ratings for products, enhancing user engagement and feedback.
- Search and Filter Functionality: Implement advanced search and filtering options for users to easily find products based on various criteria.
- Multi-language Support: Add localization features to support multiple languages, making the application accessible to a broader audience.

### Development Challenges and Learning Experience

While developing the Order Management System, I encountered several challenges, particularly as this was my first experience using Laravel for a backend application. The learning curve was steep, but I embraced the opportunity to deepen my understanding of this powerful framework.

One of the primary challenges was familiarizing myself with Laravel's structure and conventions in a short period of time. However, my prior experience with similar backend frameworks, particularly C# ASP.NET, provided a solid foundation and made the transition smoother. My knowledge in concepts such as Authentication (Session Token), RESTful APIs, and Databases (Migration, Seed) were also really helpful.

To enhance my learning experience, I dedicated time to thoroughly read the documentation for both Angular and Laravel. This proved invaluable, as it not only clarified the framework's functionalities but also helped me implement best practices in my project.

Additionally, I leveraged Generative AI tools (Cursor) to expedite my debugging processes. These tools assisted me in identifying issues more quickly and provided insights that streamlined my development workflow. This combination of resources and strategies transformed what could have been a big challenge into a rewarding learning experience.

Overall, building the Order Management System has been both challenging and fulfilling, allowing me to acquire new skills and a deeper appreciation for the Laravel framework.
