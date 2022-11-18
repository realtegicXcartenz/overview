# Overview and Notes

**Welcome curious coder!**

First thing first, our repository name is based on
```
<current module you're working>-<client/server>-<other remarks>
E.g. crm-fe-web
```

## Modules

Every module has its own **_features and menus_**
Every feature and menu has its own **_PIC_**

## Who is PIC?

_PIC_ is the person who is responsible for developing the feature/menu. So you must ask the _PIC_ to modify/change anything regarding the menu/feature that's not on your development.

## About git workflow

For the workflow, there's 3 branch for development, stagging, and production environment. When developing a feature from menu/module, make your own branch with this format

```
<dev_name>_feat:<menu>-<remarks> 
```
After committing, make a pull request to merge your current code to this branch below and don't forget to assign the reviewer to the **_PIC_** of the feature you're working on
```
<pic_name>-<menu>
```

If the **_PIC_** approves the pull request, then it will be merged to the development branch
```
development
```

This branch will be deployed and will be tested by the QA, and if it passed all the tests and user stories, it will be merged to the stagging branch for the UAT _(User Acceptance Test)_
```
stagging
```

If the stagging passed the UAT (_User Acceptance Test_) it will be deployed to production branch
```
production
```
