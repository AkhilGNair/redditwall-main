FROM nginx:1.13.0

# Remove existing nginx conf
RUN rm /etc/nginx/conf.d/default.conf

# Add my conf
ADD /nginx.conf /etc/nginx/conf.d
