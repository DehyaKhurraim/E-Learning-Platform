# E GURU (E-Learning Platform) README

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)


E GURU is an open-source, PHP-based e-learning platform designed to facilitate online education and training. It provides a robust set of features for both educators and learners, allowing for seamless communication, course management, and interactive learning experiences.

## Features

- **Course Management**: Educators can create and manage courses, including organizing lessons, assignments, quizzes, and resources.
- **User Management**: Administrators can manage users, including learners and educators, with authentication and access control.
- **Interactive Learning**: E GURU offers interactive learning experiences through various multimedia content, such as videos, documents, and interactive quizzes.
- **Communication Tools**: Educators and learners can communicate through messaging systems, discussion forums, and announcements.
- **Progress Tracking**: Learners can track their progress, view completed assignments, and monitor their overall performance.
- **Customizable Interface**: E GURU provides customization options to tailor the platform's look and feel to suit your organization's branding and preferences.
- **Multilingual Support**: E GURU supports multiple languages, allowing users from different regions to access and use the platform effectively.

## Installation

To install and run E GURU on your local development environment, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/DehyaKhurraim/E-Learning-Platform.git
   ```

2. **Navigate to the project directory**:

   ```
   cd e-guru
   ```

3. **Install dependencies**:

   ```
   composer install
   ```

4. **Configure the environment**:

   - Duplicate the `.env.example` file and rename it to `.env`.
   - Update the `.env` file with your database credentials and other relevant settings.

5. **Generate application key**:

   ```
   php artisan key:generate
   ```

6. **Run migrations**:

   ```
   php artisan migrate
   ```

7. **Seed the database** (optional):

   If you want to populate the database with sample data, run the following command:

   ```
   php artisan db:seed
   ```

8. **Start the development server**:

   ```
   php artisan serve
   ```

9. **Access the application**:

   Open your web browser and navigate to `http://localhost:8000` to access the E GURU platform.

For detailed information on configuring and deploying E GURU, please refer to the [official documentation](https://github.com/DehyaKhurraim/E-Learning-Platform).

## Contributing

Contributions are welcome! If you'd like to contribute to E GURU, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure that the project builds successfully.
4. Write tests to cover your changes (if applicable).
5. Submit a pull request detailing your changes.

Please refer to the [contributing guidelines](https://github.com/DehyaKhurraim/E-Learning-Platform/CONTRIBUTING.md) for more information.

## License

E GURU is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the software as per the terms of the license.

## Support

If you encounter any issues or have any questions or suggestions, please feel free to open an issue on the [GitHub repository](https://github.com/DehyaKhurraim/E-Learning-Platform/issues). We appreciate your feedback and will do our best to address your concerns.

## Acknowledgements

E GURU is built using various open-source libraries and frameworks. We would like to express our gratitude to the developers and

 contributors of these projects for their valuable work.

- [Laravel](https://laravel.com) - PHP web application framework
- [Vue.js](https://vuejs.org) - JavaScript framework for building user interfaces
- [Bootstrap](https://getbootstrap.com) - CSS framework
- [FontAwesome](https://fontawesome.com) - Icon toolkit

## Author

E GURU is maintained and developed by [Dehya Khurraim Siddiqui](https://github.com/DehyaKhurraim).

---

Thank you for choosing E GURU as your e-learning platform. We hope this README provides you with the necessary information to get started. Enjoy your online learning journey!
