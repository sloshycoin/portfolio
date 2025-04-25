# Resume

## Header

Brendan A. Burgee
<brendanburgee@gmail.com> • 310-592-5937 • <https://www.linkedin.com/in/brendan-burgee/> • [Portfolio URL]

## Professional Summary

Results-driven Software Developer with 6+ years of experience designing, developing, and optimizing scalable solutions in the telecommunications industry. Proven track record of driving efficiency, improving system reliability, and contributing to major deployments. Passionate about clean code, innovation, and cross-functional collaboration.

## Technical Skills

**Languages & Frameworks**: Python, JavaScript, TypeScript, Node, Express, FastAPI, Angular, React
**Tools & Platforms**: Docker, Kubernetes, Git, CI/CD Pipelines
**Databases**: MySQL, MS SQL, MongoDB, Redis
**Cloud**: Azure, IBM
**Misc**: Unix/Linux Admin, UI/UX Design, REST APIs, Agile/Scrum

## Professional Experience

Software Developer 2
Lumen Technologies
07/2023 – Present

- Developed and maintained high-availability web applications handling hundreds of concurrent, daily users.
- Spearheaded the migration of legacy systems to microservices architecture, improving service speeds by 90%.
- Mentored junior developers and led code reviews to enforce engineering best practices and promote a growth environment.

Operations Engineer 2
Centurylink
09/2018 – 07/2023

- Designed and developed a standalone framework for automating network outages and reducing time to restore.
- Introduced the first Robotic Process Automation workflow to the Global Network Operations Center.
- Implemented 40+ ticketing workflows to reduce volume in call centers.

## Education

### Degrees

Bachelor of Science in Physics
Fort Hays State University – Hays, KS

### Certifications

IBM Cloud DevOps Software Engineer
IBM Cloud Developer
IBM Full Stack Software Developer
IBM Frontend Software Developer
IBM Backend Software Developer

## Projects

**Service Support Dashboard**
Technologies: JS, TS, Python, Node, Angular, Express, MySQL, MSSQL, Git
Role: Lead
Status: In Progress
Description:
    This is a web application/dashboard that consolidates company resources from several ticketing platforms into a single page application.
    The front end is comprised of standalone Angular components offering microservices to view and manage network tickets.
    The back end is an Express API that connects to MySQL and MS SQL databases, as well as several internal REST APIs.
    Converted from a LAMP stack (Linux/Apache/MySQL/PHP) to a MEAN stack (MySQL/Express/Angular/Node) in order to improve response times and serve live data using reactive programming concepts.

**Health Check API**
Technologies: Python, Redis, Docker, Kubernetes, FastAPI, Git, CI/CD Pipelines
Role: Lead
Status: Complete
Description:
    This is a REST API that connects to network resources across North America, providing ping and authentication information for customer devices; It is leveraged by a chatbot to assist technicians in diagnosing network issues related to customer reports.
    The application is developed using FastAPI and asynchronous programming techniques to connect to hundreds of devices per second.
    Requests to the API are queued in Redis to avoid timeouts. They are also load-balanced and rate-limited to avoid negative impacts to the network.

**Automated Outage Manager**
Technologies: Python, Redis, Git, CI/CD Pipelines
Role: Lead
Status: Complete
Description:
    This is an application for monitoring network outages, and guiding technicians through the process of resolving them.
    The application intermittently scrapes outage data from a web resource, correlates outages into related events and dispatches these events to Redis queues.
    The Redis queues are managed by workflows that notify supervisors and technicians of new, scheduled or past-due work in their area.
