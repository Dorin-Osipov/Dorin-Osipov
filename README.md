# Dorin Osipov

**Senior Backend Engineer at Penspen · Leeds, UK**

I build Python services that turn complex engineering requirements into dependable software. At Penspen I take features from the first conversation with product through API design, deployment and production support. I also review code and mentor junior developers.

[Portfolio](https://dorinosipov.com/) · [LinkedIn](https://www.linkedin.com/in/dorin-osipov-69a00a221/) · [Engineering notes](https://dorinosipov.com/blog/)

## Engineering projects

- **[THEIA Pockets](https://dorinosipov.com/projects/theia-pockets)** — I designed and built the backend of Theia Pockets, that lets engineers run approved Python analyses on Theia data without setting up a Python environment. The backend takes each package from upload and approval to an isolated run on Azure Container Apps, with Redis tracking the session.
- **[Carbon Watch](https://dorinosipov.com/projects/carbon-watch)** — I led the backend and Microsoft Fabric data pipeline for a tool that helps maintenance teams see how pump condition affects energy use and emissions. Our team won Best Visualization at the Sidara × Microsoft Hackathon.

## Public code

**[Supplier Compliance API](https://github.com/Dorin-Osipov/supplier-compliance-api)** answers a procurement question: can we onboard this supplier today? FastAPI handles requests, PostgreSQL stores certificate history, and a small Python rules engine evaluates the evidence. One rule worth exploring: a valid renewal still counts when an older, expired certificate arrives later.

[Read the assessment logic](https://github.com/Dorin-Osipov/supplier-compliance-api/blob/main/compliance.py) · [Explore the test cases](https://github.com/Dorin-Osipov/supplier-compliance-api/blob/main/test_compliance.py)

**[Django Chat](https://github.com/Dorin-Osipov/django-chat)** is a compact example of real-time messaging. [Follow a message through the WebSocket consumer](https://github.com/Dorin-Osipov/django-chat/blob/main/mysite/chatapp/consumers.py) to see how Django Channels broadcasts it to a room and saves it for later.

## Background

Before Penspen, I built Python integrations for e-commerce systems at Monster Group and automated IT support tasks at Amazon. I hold a B.Eng. in Computing, Informatics and Microelectronics and earned the AWS Certified Developer – Associate credential in 2024.
