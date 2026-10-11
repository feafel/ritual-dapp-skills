FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
COPY scanner-preview.png /usr/share/nginx/html/scanner-preview.png
COPY skills-meta.jpg /usr/share/nginx/html/skills-meta.jpg
RUN sed -i 's/listen[[:space:]]*80;/listen 8080;/' /etc/nginx/conf.d/default.conf
EXPOSE 8080
