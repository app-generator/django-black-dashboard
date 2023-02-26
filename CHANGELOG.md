# Change Log

## [1.0.9] 2023-02-26
### Changes

- Bump UI version
  - [Django Black Admin](https://github.com/app-generator/django-admin-black) `v1.0.4`

## [1.0.8] 2023-02-26
### Changes

- Move to theme-based pattern
  - [Django Black Admin](https://github.com/app-generator/django-admin-black) 
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.7] 2022-09-09
### Changes

- `Bump UI version`: v1.0.2
  - `Persistent Dark-mode` via local storage

## [1.0.6] 2022-05-25
### Improvements

- Built with [Black Dashboard Generator](https://appseed.us/generator/black-dashboard/)
  - Timestamp: `2022-05-25 10:28`
- Added CDN/Static Server management
  - `ASSETS_ROOT` env variable
  
## [1.0.5] 2022-05-20
### Improvements

- Version built with [Black Dashboard Generator](https://appseed.us/generator/black-dashboard/)
- Timestamp: `2022-05-20 14:07`

## [1.0.4] 2022-01-16
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.3] 2021-09-17
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Codebase update
  - `assets` & `templates` moved to `apps` folder
  - `apps/base` renamed to `apps/home`

## [1.0.2] 2021-09-07
### Improvements & Fixes

- Bump Django Codebase to [v2.0.2](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
- Tooling:
  - Gulp SASS compilation script   
  - `Update README` - Recompile SCSS (new section)
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.1] 2021-01-13
### Improvements 

- Bump UI: [Jinja Template Black](https://github.com/app-generator/jinja-black-dashboard) v1.0.1
- Bump Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4

## [1.0.0] 2020-02-07
### Initial Release
