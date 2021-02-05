Ansible Role: [Memcached](https://memcached.org/)
=========

This role is for you to install **Memcached** and its connection tool **telnet**  

If you want this role to support more applications, you can [**submit Issues**](https://github.com/websoft9dev/role_memcached/issues/new/choose) for us.

## Requirements

Make sure these requirements need before the installation:

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu20.04 |
| Python version | Python2 Python3 |

## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before:

```
roles:
  - { role: role_common }
  - { role：role_memcached }
```


## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| memcached_version |"" | String | No |


## Example

```
memcached_version: ""
  
```

## Resources

* [Documentation](https://support.websoft9.com/docs/memcached)
* [Deploy by Image](https://apps.websoft9.com/memcached)
* [Deploy by Script](https://github.com/websoft9/ansible-memcached)


## License

[LGPL-3.0](/License.md), Additional Terms: It is not allowed to publish free or paid image based on this repository in any Cloud platform's Marketplace.

Copyright (c) 2016-present, Websoft9

## FAQ

#### Can I install the latest version of Memcached?
NO, you can only install it from the apt/yum repository 

