# Web App Portfolio Project

## Overview

The Web App Portfolio Project is a web application designed to showcase the portfolios of two members, Kirubiel and Haven. The application includes various features such as a gallery, contact form, and a detailed description of the members' skills and experiences.

## Team Members

- **Kirubiel Beza**
- **Haven Hailemariam**

## Project Architecture

### Frontend

- **HTML**: Used for the structure of the web pages.
- **CSS**: Used for styling the web pages.
- **JavaScript**: Used for adding interactive elements and client-side functionality.
- **Bootstrap**: Used for responsive design and pre-built UI components.

### Backend

- **PHP**: Used for server-side scripting and generating dynamic content.
- **XAMPP**: Used for setting up a local server, including Apache and MySQL.
- **Apache Server**: Used to serve the web application.

### Database

- **MySQL**: Used for managing and storing application data.

### Tools and Technologies

- **Visual Studio**: Used for code editing and debugging.
- **GitHub**: Used for version control and collaboration, allowing team members to work together effectively.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/web-app-portfolio.git
   cd web-app-portfolio
   ```

2. **Install XAMPP**
   - Download and install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

3. **Set Up the Apache Server and MySQL Database**
   - Start Apache and MySQL from the XAMPP control panel.
   - Create a new database in MySQL (e.g., `portfolio_db`).

4. **Configure the Database**
   - Import the provided SQL file (`database.sql`) to set up the database schema and initial data.
   ```bash
   mysql -u root -p portfolio_db < database.sql
   ```

5. **Configure the Project**
   - Update the database configuration in the project files (e.g., `config.php`) with your database credentials.

6. **Run the Application**
   - Place the project files in the `htdocs` folder of your XAMPP installation.
   - Access the application in your web browser at `http://localhost/web-app-portfolio`.

## Usage Guidelines

- **Navigating the Portfolio**: The main page provides an overview of the portfolios. Use the navigation menu to explore different sections such as the gallery and contact form.
- **Updating Content**: Content can be updated through the admin interface. Ensure you have the necessary permissions to access and modify the content.

## Future Enhancements

- **Feature Enhancements**: Adding more interactive features such as a blog section or project showcase.
- **User Feedback**: Collecting and implementing feedback from users to improve the application.
- **Deployment**: Moving the application from a local server to a live server for wider accessibility.

## Lessons Learned

- **Collaboration**: Effective communication and collaboration are key to successful project development.
- **Documentation**: Keeping detailed documentation helped in troubleshooting and maintaining the project.
- **Flexibility**: Being flexible and adaptive to changes and feedback improved the overall project outcome.

## Conclusion

The web app portfolio project has been a significant learning experience for both Kirubiel and Haven. The project not only allowed us to apply our technical skills in a practical setting but also taught us valuable lessons in collaboration, problem-solving, and project management. Moving forward, we are excited to continue enhancing the application and exploring new opportunities to showcase our skills and achievements.

## Contact

For any questions or feedback, please contact:

- Kirubiel: [kirubelkeb@gmail.com](mailto:kirubelkeb@gmail.com)
- Haven: [havenhailemariam@gmail.com](mailto:havenhailemariam@gmail.com)
```

