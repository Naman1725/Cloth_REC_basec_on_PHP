# Cloth Recommendation System

## Overview
The Cloth Recommendation System is a PHP-based web application that suggests clothing items to users based on their preferences, past choices, and current trends. This system utilizes a recommendation algorithm to provide personalized clothing suggestions, aiming to enhance the user's shopping experience.

## Features
- User authentication and profile management
- Dynamic clothing recommendations
- Customizable preferences for tailored suggestions
- Integration with external fashion APIs for trend analysis
- User feedback and rating system to improve recommendations

## Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL Database
- Apache/Nginx Server

### Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/naman-sharma/cloth-recommendation-system.git
    cd cloth-recommendation-system
    ```

2. **Install Dependencies**
    Ensure you have Composer installed, then run:
    ```bash
    composer install
    ```

3. **Set Up Database**
    - Create a MySQL database.
    - Import the `database.sql` file located in the `db` directory to set up the necessary tables.
    - Update the database configuration in the `config.php` file with your database credentials.

4. **Configure the Application**
    - Rename `.env.example` to `.env` and update the necessary configuration settings.
    - Ensure `mod_rewrite` is enabled in Apache for URL rewriting.

5. **Run the Application**
    - Start your Apache/Nginx server.
    - Access the application via `http://localhost/cloth-recommendation-system`.

## Usage
1. **User Registration and Login**
    - New users can register an account.
    - Existing users can log in using their credentials.

2. **Set Preferences**
    - Users can set their clothing preferences in their profile settings.

3. **Get Recommendations**
    - Visit the recommendations page to see personalized clothing suggestions.
    - Provide feedback on the recommendations to improve future suggestions.

## API Integration
- The system integrates with external fashion trend APIs. Ensure you have the necessary API keys and update them in the configuration file.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Fashion API providers for trend data
- Open source libraries and frameworks used in this project

## Contact
For any inquiries or support, please contact [naman.sharma@example.com].

