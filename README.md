Ansible Role: Python
=========

This Role used for install [Python](https://www.python.org/) and some popular application for Python, e.g. Ansible, Tensorflow

## Requirements

Make sure these requirements need before the installation

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu18.04 AmazonLinux|
| Python version | Python3  |
| Python Components |    |
| Runtime |  |


## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before

```
  roles:
    - {role: role_common, tags: "role_common"}
    - {role: role_python, tags: "role_python"}
```


## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| python_applications | | Dictionary and list | No |

notes: 

1. ×××××××
2. ×××××××

## Example

```
# Python application name which you want to pull, data format: Lists
python_applications: 
  - ansible
  - tensorflow
```

## FAQ
