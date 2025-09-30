📌 WPFrame – WordPress Plugin Development Framework

WPFrame is a lightweight framework designed to simplify and speed up WordPress plugin development.
It follows the Single-Instance Plugin Pattern and introduces structured architectures like MVC (Model-View-Controller) and FRC (Frontend-Routing-Controller), making plugin development more maintainable and scalable.

🚀 Features

⚡ Single-Instance Plugin Method → Avoids redundancy and ensures cleaner plugin initialization.

🧩 MVC + FRC Structure → Encourages organized development with separation of concerns.

🔗 Integration with Popular Libraries → Utilizes components from CodeIgniter 3 and Laravel (Blade templating, Eloquent ORM, etc.).

💻 WPFX (CLI Tool) → Provides simple commands for generating plugin scaffolding and speeding up development.

🔓 Open Source → Licensed under MIT, free to use, extend, and contribute.

🛠️ Tech Stack

Core Language: PHP

Platform: WordPress CMS

Database: MySQL

Libraries & Helpers: Laravel Blade, Eloquent ORM, CodeIgniter 3 Components

Tools: WPFX (CLI), Composer

📂 Project Structure
WPFrame/
│── app/              # Core application files (MVC structure)
│   ├── Controllers/  
│   ├── Models/  
│   ├── Views/  
│── config/           # Configuration files  
│── public/           # Frontend entry points  
│── routes/           # Routing (FRC concept)  
│── wpfX/             # CLI tool files  
│── wpframe.php       # Main plugin bootstrap file  

⚡ Installation

Clone this repository inside your WordPress wp-content/plugins directory:

git clone https://github.com/your-username/WPFrame.git


Activate the plugin from your WordPress Admin → Plugins section.

Run WPFX commands to scaffold new components:

php wpfX make:controller SampleController
php wpfX make:model SampleModel
php wpfX make:view sample-view

📖 Usage

Use the MVC structure for better maintainability.

Add your frontend routes in the routes/ directory.

Build custom plugins faster by extending the base classes provided in WPFrame.

🌍 Roadmap

 Add more CLI commands

 Improve documentation with examples

 Support for REST API integration

 Extend compatibility with Gutenberg Blocks

🤝 Contributing

Contributions are always welcome!

Fork the repo

Create your feature branch (git checkout -b feature-name)

Commit your changes (git commit -m 'Added feature X')

Push to the branch (git push origin feature-name)

Open a Pull Request

📜 License

This project is licensed under the MIT License – free to use, modify, and distribute.

👉 With WPFrame, developers can focus on building high-quality WordPress plugins instead of spending time on repetitive setup tasks.
