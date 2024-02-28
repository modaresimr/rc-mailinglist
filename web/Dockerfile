FROM maxking/mailman-web:0.4.6
COPY docker-entrypoint.sh /usr/local/bin/

COPY ./fixed_files/social-login.html /usr/lib/python3.8/site-packages/allauth/templates/socialaccount/login.html
COPY ./fixed_files/message.py /usr/lib/python3.8/site-packages/hyperkitty/views/message.py
COPY ./fixed_files/thread.py /usr/lib/python3.8/site-packages/hyperkitty/views/thread.py
COPY ./fixed_files/signup.html /usr/lib/python3.8/site-packages/django_mailman3/templates/account/signup.html
COPY ./fixed_files/base.html /usr/lib/python3.8/site-packages/postorius/templates/postorius/base.html
COPY ./fixed_files/account-login.html /usr/lib/python3.8/site-packages/django_mailman3/templates/account/login.html
COPY ./fixed_files/urls.py /opt/mailman-web/urls.py
COPY ./fixed_files/navbar-brand.html /usr/lib/python3.8/site-packages/hyperkitty/templates/hyperkitty/navbar-brand.html
COPY ./fixed_files/logout.html /usr/lib/python3.8/site-packages/django_mailman3/templates/account/logout.html
COPY replace_icons.sh /opt/
COPY ./fixed_files/message.html /usr/lib/python3.8/site-packages/hyperkitty/templates/hyperkitty/messages/message.html
COPY ./fixed_files/my_filter_email.py /usr/lib/python3.8/site-packages/hyperkitty/templatetags/my_filter_email.py
