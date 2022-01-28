---
title: 'Sign In'
cache_control: 'private, no-cache, must-revalidate'
login_redirect_here: false
login:
    visibility_requires_access: true
access:
    site:
        login: false
forms:
    login:
        action: null
        method: post
        fields:
            username:
                type: text
                id: username
                placeholder: PLUGIN_LOGIN.USERNAME
                label: PLUGIN_LOGIN.USERNAME
                autofocus: true
            password:
                type: password
                id: password
                placeholder: PLUGIN_LOGIN.PASSWORD
                label: PLUGIN_LOGIN.PASSWORD
downloads:
    enabled: false
content:
    items:
        - '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
---

# Sign In
### Login to test protected downloads

Username `demo` / Password `Demo2022`