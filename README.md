### python-project-architecture

```
/my_project
|-- /config                  # Configuation and setting files
|   |-- config.yaml
|   |-- settings.py
|-- /docs                    # Documentation files
|-- /tests                   # Unit and integration tests
|-- /src
|   |-- /app                 # Main application code
|   |   |-- /__init__.py     # Package initialization
|   |   |-- /modules         # Business logic modules
|   |   |-- /views           # Presentation layer (if applicable)
|   |   |-- /controllers     # Application logic layer
|   |   |-- /models          # Data models
|   |   |-- /utils           # Utility functions
|-- /config                  # Configuration files
|-- /migrations              # Database migrations (if applicable)
|-- /venv                    # Virtual environment (create this folder when using a virtual environment)
|-- /static                  # Static files (for web applications)
|-- /templates               # HTML templates (for web applications)
|-- .gitignore               # Git ignore file
|-- requirements.txt         # Project dependencies
|-- README.md                # Project README file
|-- main.py                  # Main entry point for the application
```
Make sure to save this script with a .sh extension (e.g., create_project_structure.sh). After saving, make the script executable by running:

```
chmod +x create_project_structure.sh
```

Finally, execute the script to create the project structure:

```
./create_project_structure.sh
```

### Creation of virtual environments

```
python -m venv venv
source venv/bin/activate
```
