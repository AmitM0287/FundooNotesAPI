FundooNotesAPI
Description
FundooNotesAPI is a Django project designed to provide an API for managing notes.

Requirements
Python 3.11.5

Installation
1. Clone the repository:
git clone <repository_url>

2. Navigate to the project directory: 
cd FundooNotesAPI

3. Create a virtual environment: 
python -m venv venv

4. Activate the virtual environment:
- For Windows:
  ```bash
  venv\Scripts\activate
  ```
- For macOS and Linux     ```bash
  source venv/bin/activate
  ```
5. Install required packages:
```bash
pip install -r requirements.txt

Usage
After installing the required packages, you can start using the FundooNotesAPI for managing notes through the provided API endpoints.

API Endpoints
/api/notes/: GET, POST
/apinotes/<note_id>/: GET, PUT, DELETE
/api/categories/: GET, POST
/api/categories/<category_id>/: GET, PUT, DELETE

Contributors
[Amit Manna]
