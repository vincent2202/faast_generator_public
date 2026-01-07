
# Faast Generator

Faast Generator helps you move faster by generating a working CRUD REST API
from your Django models in one command.

Building an MVP or an internal tool shouldn’t start with rewriting the same
Django REST Framework boilerplate over and over again.

Faast Generator removes that setup friction so you can focus on what actually
matters.

---

👉 Purchase and access instructions:  
https://pawlowskivfi.gumroad.com/l/pmsmye


## The problem

When building with Django:

- your models are ready
- but turning them into a usable API takes hours
- serializers, viewsets, routes, filters… again and again

That delay kills momentum, especially for MVPs and internal tools.

---

## Why Faast Generator

Faast Generator was built by a senior Django developer who has shipped
multiple products, MVPs, and internal tools — and got tired of losing energy
to repetitive setup work.

The goal is **not** to replace your decisions.

The goal is to get you past the boring part.

- You stay in control
- You own the generated code
- Nothing runs at runtime
- Nothing is hidden

---

## How it works

1. You keep your Django models  
2. You run one command  
3. You get a working CRUD REST API you can immediately use  

No framework to adopt.  
No runtime magic.  
Just generated code you can modify freely.

---

## What you get

- Ready-to-use CRUD REST API generated from Django models
- OpenAPI / Swagger documentation
- Opinionated, predictable DRF structure
- Code lives in your project (no lock-in)

### Generated components

- Serializers (including nested relationships)
- ViewSets (pagination, filtering, search)
- Filters generated from field types
- Admin configuration
- URL routing
- OpenAPI / Swagger documentation
- TypeScript type definitions (**Pro version only**)
- Automatic updates to `settings.py` and `urls.py`

---

## Usage

```bash
python manage.py faast_generator init myproject
python manage.py faast_generator generate --app customers
````

After generation, your API is immediately usable.

---

## Features

* Handles `ForeignKey` and `ManyToMany` relationships
* Through-model support (avoids circular references)
* External model stubs
* Flexible pagination (tables vs dropdowns)
* Skeleton files for customization (never overwritten)
* Clean uninstall — generated code keeps working

---

## Installation

Faast Generator is distributed as a private Python package.

Install via `pip` after purchase:

```bash
pip install faast-generator
```

Access to the private GitHub repository is provided after checkout.

---

## What it deliberately does NOT do

* Authentication or permissions
* Business logic
* Frontend UI

Faast Generator removes **setup friction**, not thinking.

---

## Who this is for

* Django developers building MVPs
* Prototypes and internal tools
* Projects where speed matters more than perfection
* Anyone tired of rewriting the same DRF boilerplate

---

## Requirements

* Python 3.10+
* Django 4.2+

---

## License

Per-developer license.
Generated code can be used freely in personal or commercial projects.

👉 Purchase and access instructions:  
https://pawlowskivfi.gumroad.com/l/pmsmye


