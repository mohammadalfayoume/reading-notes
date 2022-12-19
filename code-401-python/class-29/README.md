# read 29: API Deployment

## Configuring Django Settings: Best Practices

## Managing Django Settings: Issues

1. Different environments 

Usually, you have several environments: local, dev, ci, qa, staging, production, etc. Each environment can have its own specific settings (for example: DEBUG = True, more verbose logging, additional apps, some mocked data, etc). You need an approach that allows you to keep all these Django setting configurations.

2. Sensitive data

You have SECRET_KEY in each Django project. On top of this there can be DB passwords and tokens for third-party APIs like Amazon or Twitter. This data cannot be stored in VCS.

3. Sharing settings between team members

You need a general approach to eliminate human error when working with the settings. For example, a developer may add a third-party app or some API integration and fail to add specific settings. On large (or even mid-size) projects, this can cause real issues.

4. Django settings are a Python code

This is a curse and a blessing at the same time. It gives you a lot of flexibility, but can also be a problem – instead of key-value pairs, settings.py can have a very tricky logic.

## Setting Django Configurations: Different Approaches

There is no built-in universal way to configure Django settings without hardcoding them. But books, open-source and work projects provide a lot of recommendations and approaches on how to do it best. Let’s take a brief look at the most popular ones to examine their weaknesses and strengths.

## Referances

https://djangostars.com/blog/configuring-django-settings-best-practices/
