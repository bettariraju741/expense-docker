FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.con /etc/nginx/nginx.conf
COPY expense.conf /etc/nginx/default.d/expense.conf
