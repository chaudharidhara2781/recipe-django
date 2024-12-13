# Recipe Manager

<p>A simple Django-based web application that allows users to view a list of recipes and add new ones. The project starts with three default recipes: Scrambled Eggs, Cake Bread, and Tomato Soup.</p>

<p>This project is beginner-friendly and demonstrates the basics of Django, including models, views, forms, templates, and static files.</p>

<h2>Features</h2>
<ul>
  <li><strong>View Recipes:</strong> Browse a list of existing recipes with their ingredients and instructions.</li>
  <li><strong>Add Recipes:</strong> Add new recipes to the list via a simple form.</li>
  <li><strong>Default Recipes:</strong> Comes preloaded with three recipes to get started.</li>
  <li><strong>Minimalistic Design:</strong> Includes a simple and clean CSS file for styling.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Backend:</strong> Django (Python)</li>
  <li><strong>Frontend:</strong> HTML, CSS</li>
  <li><strong>Database:</strong> SQLite (default Django database)</li>
</ul>

<h2>Installation and Setup</h2>
<ol>
  <li>Clone the repository:
    <pre>
    <code>
git clone https://github.com/your-username/recipe-manager.git
cd recipe-manager
    </code>
    </pre>
  </li>
  <li>Create a virtual environment and activate it:
    <pre>
    <code>
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
    </code>
    </pre>
  </li>
  <li>Install the required dependencies:
    <pre>
    <code>
pip install -r requirements.txt
    </code>
    </pre>
  </li>
  <li>Apply migrations:
    <pre>
    <code>
python manage.py makemigrations
python manage.py migrate
    </code>
    </pre>
  </li>
  <li>Run the development server:
    <pre>
    <code>
python manage.py runserver
    </code>
    </pre>
  </li>
  <li>Open the app in your browser at <a href="http://127.0.0.1:8000/">http://127.0.0.1:8000/</a>.</li>
</ol>


<h2>How to Use</h2>
<ol>
  <li>Visit the homepage to view the list of recipes.</li>
  <li>Click <strong>"Add a new recipe"</strong> to submit a new recipe using the form.</li>
  <li>View the updated list with your newly added recipe.</li>
</ol>



![Screenshot 2024-12-13 173853](https://github.com/user-attachments/assets/258920be-690b-47e4-a3d9-aa6adac065cd)

![Screenshot 2024-12-13 173816](https://github.com/user-attachments/assets/3a8cc772-e0b6-40b2-812c-b0ae05c4a1f7)

