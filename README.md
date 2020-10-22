# New Relic One Application Boilerplate

This boilerplate aims to provide a quick start into NR1 application development.

Demonstrates the use of:

- React Context
- NR1 NerdGraphQuery, NerdStorage, Charts, Entity Search etc.
- Using third party component libraries

## Helpful links

- https://developer.newrelic.com/
- https://reactjs.org/docs/context.html
- https://react.semantic-ui.com/

## Getting Started

Install dependencies

```
npm i
```

Regenerate the uuid for your target account

```
nr1 nerdpack:uuid -gf
or with a specific profile
nr1 nerdpack:uuid -gf --profile=demotron-v2
```

Running locally

```
nr1 nerdpack:serve
or with a specific profile
nr1 nerdpack:serve --profile=demotron-v2
```

Visit https://one.newrelic.com/?nerdpacks=local and :sparkles:

Deploying

```
nr1 nerdpack:publish [--profile=your_profile_name]
nr1 nerdpack:deploy [-c [DEV|BETA|STABLE]] [--profile=your_profile_name]
nr1 nerdpack:subscribe [-c [DEV|BETA|STABLE]] [--profile=your_profile_name]
```
