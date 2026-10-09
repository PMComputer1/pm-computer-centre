# PM Computer Centre — Complete Website

## Included
- Responsive public website based on the supplied PM Computer Centre page.
- Online admission form saved to MySQL.
- Student portal and login.
- Admin login/panel with student records.
- Add/edit students.
- Fee collection and receipt records.
- Certificate issuing and print-ready certificate.
- WhatsApp callback/contact workflow remains available in the supplied public page.

## Installation (XAMPP/cPanel)
1. Create a MySQL database named `pm_computer_centre`.
2. Import `db.sql` in phpMyAdmin.
3. Upload all files to your hosting `public_html` folder.
4. Edit database credentials at the top of `config.php`.
5. Open `index.html` for the public site and `register.php` for online admission.
6. Login at `login.php`.

### Important admin security step
The SQL contains a setup administrator hash. For production, create/change the admin password immediately after installation. Do not keep default credentials in a public deployment.

## Existing website content
The original supplied HTML content was retained as the public `index.html`; the new PHP modules add the database-backed functions.
