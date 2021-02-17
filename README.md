# Backend
This is the back-end for the todo list app created with Django. It was created to show my improved Django development skills. This backend uses a simple sqlite database to allow access to front-end application to full CRUD functionality through an api. It also employs a slightly customized version of Django's built in administration suite.

# Techstack
- Django
- HTML
- CSS
- Python
- SQL
  
# Key Learnings
1. Any front-end framework/library/package can consume a django api.
2. React is a highly productive way to create a front-end.
3. Bootstrap and Reactstrap accelerate building attractive React UIs.

# Next
- Replace SQLite with Postgres when put into production
- Deploy using LXD/LXC, Docker/Kubernetes to Digital Ocean [Hatch Program]
- Use cloudflare CDN to reduce API calls
- Ensure architected correctly using encapsulation, separation of business logic from functionality, and other key concepts
- Incorporate Rust to offload computationally intensive tasks to much faster compiled binaries through python
- Convert to a type of master API that pulls from other APIs used by deliver the todo application (build this functionality to continue using SQL and Django's ORM or learn a new query language and switch to GraphQL)

# Inspiration
- https://www.django-rest-framework.org/
- https://www.python.org/
- https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react