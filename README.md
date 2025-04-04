<h1 align="center">🧾 Bill Generation System</h1>

<p align="center">
  A powerful web-based application built with <b>Django</b> to manage products and generate printable customer bills.
</p>

---

## 🚀 Features

- 🛒 Add, update, and delete products
- 🧾 Generate itemized bills for customers
- 📥 Download bills as PDF
- 🗂 View past billing history
- 🔐 Admin dashboard for product management

## 🛠 Tech Stack

- **Backend:** Django (Python)
- **Database:** SQLite (default)
- **Frontend:** HTML, CSS, Bootstrap
- **PDF Generation:** ReportLab / WeasyPrint

## 📁 Project Structure
<h2>📁 Project Structure</h2>

<table>
  <thead>
    <tr>
      <th>Path</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>app/</code></td>
      <td>Main Django app for billing logic</td>
    </tr>
    <tr>
      <td><code>app/admin.py</code></td>
      <td>Admin panel configurations</td>
    </tr>
    <tr>
      <td><code>app/models.py</code></td>
      <td>Django models for products and bills</td>
    </tr>
    <tr>
      <td><code>app/views.py</code></td>
      <td>Handles business logic and rendering</td>
    </tr>
    <tr>
      <td><code>app/urls.py</code></td>
      <td>App-specific URL routes</td>
    </tr>
    <tr>
      <td><code>app/templates/</code></td>
      <td>HTML templates</td>
    </tr>
    <tr>
      <td><code>app/static/</code></td>
      <td>Static files like CSS, JS</td>
    </tr>
    <tr>
      <td><code>dj24/</code></td>
      <td>Project configuration folder</td>
    </tr>
    <tr>
      <td><code>dj24/settings.py</code></td>
      <td>Django project settings</td>
    </tr>
    <tr>
      <td><code>dj24/urls.py</code></td>
      <td>Root URL configuration</td>
    </tr>
    <tr>
      <td><code>dj24/wsgi.py</code></td>
      <td>WSGI entry point for deployment</td>
    </tr>
    <tr>
      <td><code>manage.py</code></td>
      <td>Django management utility</td>
    </tr>
    <tr>
      <td><code>db.sqlite3</code></td>
      <td>Default SQLite database</td>
    </tr>
    <tr>
      <td><code>media/</code></td>
      <td>Uploaded files and images</td>
    </tr>
    <tr>
      <td><code>requirements.txt</code></td>
      <td>Python dependencies list</td>
    </tr>
  </tbody>
</table>

## 🧩 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/VishalTelukula/InvoiceGen.git
   cd InvoiceGen
   python -m venv venv
   pip install -r requirements.txt
   python manage.py runserver




