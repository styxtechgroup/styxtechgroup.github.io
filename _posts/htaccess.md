---
permalink: ".htaccess"
layout: none
---

RewriteEngine On
RewriteCond %{HTTP_HOST} !^www\.styxtechgroup\.com$ [NC]
RewriteRule ^(.*)$ https://www.styxtechgroup.com/$1 [R=301,L]