# Change Log

## [1.0.20] 2024-11-27
### Changes

> Update RM Links

- 👉 [Django Black Dashboard](https://app-generator.dev/product/black-dashboard/django/) - `Product Page`
- 👉 [Django Black Dashboard](https://app-generator.dev/docs/products/django/black-dashboard/index.html) - `Complete Information` and Support Links
  - [Getting Started with Django](https://app-generator.dev/docs/technologies/django/index.html) - a `comprehensive tutorial`
  - `Configuration`: Install Tailwind/Flowbite, Prepare Environment, Setting up the Database 
  - `Start with Docker`
  - `Manual Build`
  - `Start the project`
  - `Deploy on Render`

## [1.0.19] 2024-11-11
### Changes

- Update RM Links:
  - 👉 [Django Black Dashboard](https://app-generator.dev/docs/products/django/black-dashboard/index.html) - **Complete Documentation**
  - 👉 [Django Black Dashboard](https://app-generator.dev/product/black-dashboard/django/) - Product Page
  - 👉 [Get Support](https://app-generator.dev/ticket/create/) via Email and Discord

## [1.0.18] 2024-05-18
### Changes

- Updated DOCS (readme)
  - [Custom Development](https://appseed.us/custom-development/) Section
  - [CI/CD Assistance for AWS, DO](https://appseed.us/terms/#section-ci-cd)

## [1.0.17] 2024-04-16
### Changes

- Use `Vite` for SCSS Compilation
- Fix Charts on MAIN dashboard
- Added HOT Reload (templates & static)

## [1.0.16] 2024-03-05
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
  - New Pricing: `$3,999`

## [1.0.15] 2024-03-02
### Changes

- Deprecate `distutils`
  - use `str2bool`
- Update Deps 
  - `requirements.txt`  
- Update README: [PRO Version](https://appseed.us/product/black-dashboard-pro/django/), List features
  - `API`, **Charts** 
  - **DataTables** (Filters, Export)
  - **Celery**
  - **Media Files Manager**
  - **Extended User Profiles**

## [1.0.14] 2023-02-14
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
- Minor Changes (readme)

## [1.0.13] 2023-10-24
### Changes

- Update Dependencies 
- Update README 

## [1.0.12] 2023-02-27
### Changes

- Bump UI version, [Django Black Admin](https://github.com/app-generator/django-admin-black) `v1.0.8`
- Update local templates & Static

## [1.0.11] 2023-05-03
### Changes

- Bump UI Version
- Added Local Templates and STATICs
- Added Gulp Tooling for SCSS Compilation
- Update DOCS (readme) 

## [1.0.10] 2023-02-27
### Changes

- Bump UI version
  - [Django Black Admin](https://github.com/app-generator/django-admin-black) `v1.0.6`

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
