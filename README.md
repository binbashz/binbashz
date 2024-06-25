# Hi there

## About Me


```
class Education:
    def __init__(self, degree, institution, location):
        self.degree = degree
        self.institution = institution
        self.location = location

    def to_dict(self):
        return {
            "degree": self.degree,
            "institution": self.institution,
            "location": self.location
        }

class Experience:
    def __init__(self, position, company, location, date, description):
        self.position = position
        self.company = company
        self.location = location
        self.date = date
        self.description = description

    def to_dict(self):
        return {
            "position": self.position,
            "company": self.company,
            "location": self.location,
            "date": self.date,
            "description": self.description
        }

class Developer:
    def __init__(self, name, occupation, location, email, github, objective, education, experience, skills, languages):
        self.name = name
        self.occupation = occupation
        self.location = location
        self.email = email
        self.github = github
        self.objective = objective
        self.education = education
        self.experience = experience
        self.skills = skills
        self.languages = languages

    def to_dict(self):
        return {
            "name": self.name,
            "occupation": self.occupation,
            "location": self.location,
            "email": self.email,
            "github": self.github,
            "objective": self.objective,
            "education": [edu.to_dict() for edu in self.education],
            "experience": [exp.to_dict() for exp in self.experience],
            "skills": self.skills,
            "languages": self.languages
        }

# Define data
mauricio_education = Education("Foundations in Computer Science", "Holberton School", "Montevideo")

# Define experience
project1 = Experience("Full Stack Developer", "Holberton School - Montevideo", "Montevideo", "2022-09 - 2023-11",
                      "Expertise in Python, C, JavaScript, HTML, CSS, SQL, Linux, and system administration.")
project2 = Experience("Final Project", "Holberton School", "-", "Ongoing",
                      "Online platform for car rental services.")

mauricio_experience = [project1, project2]

# Create Developer instance
mauricio = Developer(
    name="Mauricio",
    occupation="Full Stack Developer",
    location="Uruguay",
    email="imcorreamauricio@gmail.com",
    github="http://github.com/binbashz",
    objective="Passionate Full Stack Developer exploring key concepts in Frontend and Backend development.",
    education=[mauricio_education],
    experience=mauricio_experience,
    skills=[
        "HTML/CSS", "JavaScript", "Python", "SQL", "Node.js", "API Development",
        "Flask-SQLAlchemy", "RESTful APIs", "JSON", "Data structures", "C programming",
        "Linux", "Web Development", "UI Enhancement", "Databases", "HTTP",
        "Backend Development", "Frontend"
    ],
    languages=[
        {"language": "Spanish", "proficiency": "Native"},
        {"language": "English", "proficiency": "Advanced"}
    ]
)

# Convert to dictionary
mauricio_data = mauricio.to_dict()
print(mauricio_data)


```

## Goal

My knowledge in these areas is continuously evolving, and my goal is to keep learning and growing professionally.
 I'm equally interested in both backend and frontend development. On the backend,
I'm excited to delve into designing robust and scalable systems that cater to user needs.
 On the frontend, I'm motivated by creating intuitive and engaging user interfaces that provide an optimal experience for end-users.

## Focus on Hands-On Experience

Currently, my focus is on gaining hands-on experience and applying what I've learned in real work scenarios.
 I'm keen on connecting with industry professionals, learning from their experiences, and contributing in any way I can.

## Let's Connect!

If you share similar interests, have advice for my professional growth, or just want to chat about technology,
 feel free to reach out! I'm excited about the opportunity to learn and grow alongside the developer community.
 mdatanode@outlook.com

## Backend:

[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" alt="Django Logo" width="20"/> Django](https://www.djangoproject.com/)
[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" alt="Flask Logo" width="20"/> Flask](https://flask.palletsprojects.com/en/2.0.x/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js Logo" width="20"/> Express.js](https://expressjs.com)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js Logo" width="20"/> Node.js](https://nodejs.org)


## Databases:
[<img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="MSSQL Logo" width="20"/> Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB Logo" width="20"/> MongoDB](https://www.mongodb.com/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL Logo" width="20"/> MySQL](https://www.mysql.com/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL Logo" width="20"/> PostgreSQL](https://www.postgresql.org)

## Frontend:
[<img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter Logo" width="20"/> Flutter](https://flutter.dev)
[<img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="Dart Logo" width="20"/> Dart](https://dart.dev)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React Logo" width="20"/> React](https://reactjs.org/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap Logo" width="20"/> Bootstrap](https://getbootstrap.com)
[<img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js Logo" width="20"/> Next.js](https://nextjs.org/)
[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS Logo" width="20"/> Tailwind CSS](https://tailwindcss.com/)


## Programming Languages:
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C Logo" width="20"/> C](https://www.cprogramming.com/)
[<img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash Logo" width="20"/> Bash](https://www.gnu.org/software/bash/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript Logo" width="20"/> JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python Logo" width="20"/> Python](https://www.python.org)

## Tools and Others:
[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" alt="HTML Logo" width="20"/> HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" alt="CSS Logo" width="20"/> CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
[<img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git Logo" width="20"/> Git](https://git-scm.com/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux Logo" width="20"/> Linux](https://www.linux.org/)
[<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="Photoshop Logo" width="20"/> Photoshop](https://www.photoshop.com/en)
[<img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman Logo" width="20"/> Postman](https://postman.com)






![Contributions](https://github-readme-streak-stats.herokuapp.com/?user=binbashz)





