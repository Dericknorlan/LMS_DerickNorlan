## About the Project
The Laravel Library Management using the Laravel 11 framework.


## User Role
- **Admin** can add/remove librarian and has authority to approve or reject collection update requested by the librarian.
- **Librarian** can manage library inventory (Create, Read, Update, Delete).

## Models
- **Books**: Consists of `title`, `author`, `publisher`, `year`, `type` (Printed book or Ebook), and `is_approved` (Request status) attributes.
- **CDs**: Consists of `title`, `artist`, `genre`, `stock` and `is_approved` (Request status) attributes.
- **Journals**: Consists of `title`, `author`, `publish_date`, `abstract` and `is_approved` (Request status) attributes.
- **Newspapers**: Consists of `title`, `publisher` (Kompas, Tribun Timur, or Fajar), `publish_date`, `is_available` and `is_approved` (Request status) attributes.
