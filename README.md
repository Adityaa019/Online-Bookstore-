# [Bies Store](https://bies-bookstore.azurewebsites.net/)
BiesStore is an e-commerce bookstore built with ASP.NET Core MVC, using Entity Framework Core and Microsoft SQL Server as the backend technologies. The project uses ASP.NET Core Identity for authentication and authorization, and follows the repository and unit of work pattern for data access. The project is structured using n-tier architecture, with separate projects for the web application, models, data access, and utilities.

[Click Here for Demo And ScreenShots](./Demo)
# Project Description
BiesStore allows customers to browse and purchase books, while companies can sell their products through the platform. The project consists of three roles: Customer, Company, and Admin. Customers can add products to the shopping cart, view and update the shopping cart, and complete orders via Stripe payment processing. Companies can add product listings, edit or delete existing listings, and manage their orders. Admins have control over the entire operation, including categories, products, and orders.

# External Technologies
The project uses DataTables for AJAX tables with CRUD operations, TinyMCE for rich text editing, Bootstrap for UI building and theming, Toastr for toast notifications, Sweet Alert 2 for modal popup windows, Stripe for payment processing, and now has email verification and order notification capabilities through MimeKit and MailKit.

