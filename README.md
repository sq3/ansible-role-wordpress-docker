# Ansible wordpress-docker role

wordpress-docker role supports most of the office wordpress docker
container options and has some default settings for my behaviors

## Supported Options

    volumes:
    - "{{ wordpress_data }}:/usr/src/wordpress/wp-content"
    env:
      WORDPRESS_DB_HOST: "{{ wordpress_db_host }}"
      WORDPRESS_DB_USER: "{{ wordpress_db_user }}"
      WORDPRESS_DB_PASSWORD: "{{ wordpress_db_password }}"
      WORDPRESS_DB_NAME: "{{ wordpress_db_name }}"
