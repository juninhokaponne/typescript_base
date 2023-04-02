# Typescript_base

Typescript_base is a repository for you that need to start a new project with a boilerplate with all basic configs.

### Common errors and how to resolve

> [eslint] Delete `CR` [prettier/prettier]

You can resolve this with next command in your **.eslintrc**

```rules: {
  'prettier/prettier': [
    'error',
    {
      endOfLine: 'auto',
    },
  ],
}
```
