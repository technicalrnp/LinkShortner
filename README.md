# 🚀 Link Shortener

A fast and straightforward PHP-based Link Shortener. No login or registration required. Just input the URL, and get a short URL instantly!

## Setup

### Prerequisites

- PHP installed on your server.
- MySQL database (e.g., using MySQL or MariaDB).
- Git for cloning the repository.

### Steps

1. **Clone the GitHub Repository:**

    ```bash
    git clone https://github.com/codeterrayt/LinkShortner.git
    cd LinkShortner
    ```

2. **Setup the Database:**

    - Create a database named `link_shortner_db`.

    - Import the SQL file `link_shortner_table.sql` into your database.

        ```bash
        mysql -u your_username -p link_shortner_db < link_shortner_table.sql
        ```

3. **Configure Web Server:**

    - Make sure your web server is configured to serve the files in the repository.

4. **Run the Application:**

    - Open your browser and navigate to the application.

## Usage

1. **Shorten a URL:**

    - Visit the application and input the URL you want to shorten.

    - Get the short URL instantly!

## File Structure

- `index.php`: Main application file.
- `link_shortner_table.sql`: SQL file for database setup.

## Notes

- This Link Shortener is designed for simplicity and speed.
- No login or registration required.
- Ensure proper security measures before deploying in a production environment.

🚀 Happy Link Shortening! 🔗
