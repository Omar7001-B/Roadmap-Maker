# Roadmap Maker

A professional roadmap creation and management application built with Spring Boot.

## 🚀 Features

- User Authentication and Authorization (OAuth2)
- Secure API endpoints
- Database integration with JPA
- Email notifications
- Modern and responsive UI with Thymeleaf
- RESTful API architecture

## 🛠️ Technologies

- Java 23
- Spring Boot 3.4.3
- Spring Security
- Spring Data JPA
- Spring Mail
- Thymeleaf
- OAuth2
- Project Lombok
- Maven

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Java Development Kit (JDK) 23 or later
- Maven 3.6+
- Your favorite IDE (IntelliJ IDEA recommended)

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Roadmap-Maker.git
cd Roadmap-Maker
```

2. Build the project:
```bash
./mvnw clean install
```

3. Run the application:
```bash
./mvnw spring-boot:run
```

The application will be available at `http://localhost:8080`

## 🔑 Configuration

Create an `application.properties` or `application.yml` file in `src/main/resources` with your configuration:

```properties
# Database Configuration
spring.datasource.url=your_database_url
spring.datasource.username=your_username
spring.datasource.password=your_password

# Mail Configuration
spring.mail.host=your_smtp_host
spring.mail.port=your_smtp_port
spring.mail.username=your_email
spring.mail.password=your_password

# OAuth2 Configuration
spring.security.oauth2.client.registration.google.client-id=your_client_id
spring.security.oauth2.client.registration.google.client-secret=your_client_secret
```

## 🚀 Usage

1. Access the application through your web browser
2. Log in using your credentials or OAuth2 provider
3. Create and manage your roadmaps
4. Share and collaborate with team members

## 🧪 Running Tests

To run the automated tests:

```bash
./mvnw test
```

## 📦 Building for Production

To create a production build:

```bash
./mvnw clean package -P prod
```

The built JAR file will be located in the `target` directory.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Spring Boot team for the excellent framework
- The open-source community for their invaluable contributions

## 📞 Support

For support, email your-email@example.com or create an issue in the repository.
