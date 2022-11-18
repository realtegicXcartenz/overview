# Overview and Notes

**Welcome curious coder!**

First thing first, our repository name is based on
```
<current module you're working>-<client/server>-<other remarks>
E.g. crm-fe-web
```

## Modules

Every module has its own **_features and menus_**.
Every feature and menu has its own **_PIC_**

## Who is PIC?

_PIC_ is the person who is responsible for developing the feature/menu. So you must ask the _PIC_ to modify/change anything regarding the menu/feature that's not on your development.

## About git workflow

For the workflow, there's 3 branch for development, stagging, and production environment. When developing a feature from menu/module, make your own branch with this format

```
<dev_name>_feat/<menu>-<remarks> 
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

## About making pull request
![image](https://user-images.githubusercontent.com/85435591/202667047-e4537f10-3c1a-4340-a365-3a1b7ed1e4ca.png)

Choose the branch with the _PIC_ you're developing on and make the reviewers and assignees the _PIC_ and don't forget to add labels about what you're working on

**PLEASE MAKE A DESCRIPTIVE COMMIT MESSAGE FOR THE ASSINGESS AND REVIEWERS PURPOSE TO UNDERSTAND WHAT YOU'VE DEVELOPED**

## About all the PIC

### CRM PIC
- Nicholas Fortune (jayfortune03) (deployment on dev, stagging, prod, chat WA, mobile app)
- Taufik Ramadhan (deployment on dev, stagging, prod, chat WA)
- Vira (chat Chatwoot)
- Rafie (chat chatwoot & contact)
- Iwan (contact)


#### P.S. Lord CTO will haunt you.
