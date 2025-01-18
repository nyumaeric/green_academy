# Green Academy

## Description

Green Academy is a Django web application designed for managing students and courses, with a focus on environmental education. This platform aims to provide a comprehensive system for educational institutions to manage their academic operations efficiently.

## Features

- **Student Management System**: Manage student records, including enrollment, attendance, and grades.
- **Course Catalog and Management**: Maintain a catalog of courses, including course descriptions, syllabi, and schedules.
- **Future Features**: Planned enhancements include an enrollment system, course materials upload, and more.

## Prerequisites

- Python 3.8 or higher
- Django
- A code editor
- Basic knowledge of Python and Django

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Williedaniels/green_academy.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd green_academy
   ```

3. **Create and activate a virtual environment**:

   - On Mac/Linux:

     ```bash
     python3 -m venv env
     source env/bin/activate
     ```

   - On Windows:

     ```bash
     python -m venv env
     env\Scripts\activate
     ```

4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run database migrations**:

   ```bash
   python manage.py migrate
   ```

6. **Start the development server**:

   ```bash
   python manage.py runserver
   ```

## Usage

- Access the application at [http://localhost:8000/](http://localhost:8000/).
- Additional usage instructions will be provided as the project develops.

## Project Structure

- `green_academy/`: Contains Django project files.
  - `settings.py`: Project settings configuration.
  - `urls.py`: URL routing configuration.
  - `wsgi.py`: WSGI configuration for the application.
- `students/`: App for managing student records.
- `courses/`: App for managing course catalog and details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to contribute to the project.

## License

This project is licensed under the ALU License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, contact me at [w.daniels@alustudent.com](mailto:w.daniels@alustudent.com).

---
