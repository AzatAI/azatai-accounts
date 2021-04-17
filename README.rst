=====
AzatAI Accounts Django App
=====

AzatAI Accounts is a Django Reusable app with builtin templates for login, logout, registering and password reset functionality.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "account" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'account',
    ]

2. Include the account URLconf in your project urls.py like this::

    path('account/', include('account.urls')),

3. Run ``python manage.py migrate`` to create the account models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a account (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/account/ to participate in the account.