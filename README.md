# Openldap GitHub Action

This action is based on the [dinkel/openldap](https://github.com/dinkel/docker-openldap) image

# Usage

Basic:
```yaml
steps:
- uses: virgilio21/openldap-action@v1
  with:
    adminPassword: 'supersecret'
    domain: 'spaghetti.com'  
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)