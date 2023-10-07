# BlueSkyUnlimited for the Course: Practice Enterprise 2
- BlueSkyUnlimited facilitates air cargo logistics for the customers by efficiently managing the transportation of goods via various airlines.
- I **HIGHLY RECOMMEND** you to check "PersonelSprintLog" documents for detailed explanations of any aspect of the project.

## Course: Practice Enterprise 2
- "The students work during one semester on a joint project.  On the one hand, they will put their acquired theoretical and practical knowledge into practice in order to realize something concrete, while on the other hand they will use other skills ("soft skills") to bring this to a successful conclusion as a team."
- For more information: https://onderwijsaanbodmechelenantwerpen.thomasmore.be/syllabi/e/YT0902E.htm#activetab=doelstellingen_idp1823088


## PersonalSprintLogs Summary
- Introduction of the MVC (Model-View-Controller) pattern in Laravel, with concise tutorials provided to the team, covering the following topics:
    - Laravel Basics.
    - Model Relationships.
    - Debugging with Tinker.
    - Laravel Seeders & Factory Class.
    - Utilization of Laravel Eloquent ORM for Database Manipulations.
- Implementation of QR Code functionality for Shipments.
- Implementation of Waypoints to divide the focus on shipment routes for the optimal solution.
- Integration of the AirLabs API to populate the database with precise Airport Locations.
- Utilization of a combination of BingMaps API and AirLabs API to display relevant Airport data within the graphical layout of shipment tracking.
- Development of shipment evaluation features to empower Logistic Coordinators in their tasks.


## How to Run the Project

## How to Run the Project
- Clone the Project
- Set Up XAMPP (or Other Web and Database Servers):
    - Install and configure XAMPP (or any other web and database servers supported by Laravel). Ensure that Apache and MySQL are running.
- Set Up PHP:
    - Install PHP and add it to your system's PATH if it's not already done.
- Set Up Composer:
    - Install Composer and add it to your system's PATH if it's not already done.
- Set Up NodeJS
	- Install NodeJS and add it to your system's PATH if it's not already done.
- Open the Project with Your Preferred IDE:
    - Open the downloaded Laravel project in your desired Integrated Development Environment (IDE), such as VSCode.
 
      
- Configure the Environment Variables:
    - Locate the .env file in your Laravel project directory and make the following changes:
        - Change the APP_URL to your desired port (default: localhost:8000).
        - Change DB_DATABASE to your desired database name (default: bluesky).
        - Enter your BingMaps & AirLabs API keys into relevant rows.
            - Both APIs currently offer free usage options:
                - https://airlabs.co/
                - https://www.bingmapsportal.com/

- Access the Project Directory with a CLI Tool:
    - Open your project directory in the CLI tool of your choice, such as VSCode's integrated terminal.
    - Execute the Following Commands:
        - Inside your project's path, run the following commands one by one:
            - composer install
            - composer update
            - npm ci
            - php artisan migrate --seed
            - php artisan key:generate
            - php artisan bootstrap
            - php artisan serve --port=<selected_port>
            - npm run dev

