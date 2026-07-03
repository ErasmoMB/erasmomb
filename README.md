# 💻 Erasmo MB --- Interactive GitHub Profile

> A GitHub profile designed as if it were a VS Code workspace.

``` text
📁 portfolio
│
├── about.ts
├── projects.json
├── ai.py
├── stack.yml
├── experience.log
├── contact.md
└── terminal.sh
```

------------------------------------------------------------------------

## `about.ts`

``` ts
export const developer = {
  name: "Erasmo Montufar Barrientos",
  alias: "Erasmo MB",
  role: "Full Stack Engineer + AI Engineer",
  location: "Lima, Peru",
  focus: [
    "Artificial Intelligence",
    "LLMs & RAG",
    "Cloud Computing",
    "Computer Vision",
    "Production Systems"
  ],
  mission: "Transform ideas into software people actually use.",
  available: true
};

export async function build(idea: Problem) {
  const model = await train(idea);
  return deploy({
    frontend: "Next.js",
    backend: "FastAPI",
    cloud: "AWS"
  });
}
```

------------------------------------------------------------------------

## `projects.json`

``` json
{
  "featured": [
    {
      "name": "ChevasTextil ERP",
      "status": "building",
      "stack": ["Next.js","FastAPI","PostgreSQL","AWS"]
    },
    {
      "name": "Legal AI Peru",
      "status": "production",
      "stack": ["Gemini","RAG","Vector DB"]
    },
    {
      "name": "Scientific Dashboard",
      "status": "production",
      "stack": ["React","FastAPI","Scikit-Learn"]
    },
    {
      "name": "AWS Vulnerability Scanner",
      "status": "production",
      "stack": ["Python","Lambda","boto3"]
    }
  ]
}
```

------------------------------------------------------------------------

## `ai.py`

``` python
class Engineer:

    def __init__(self):
        self.specialties = [
            "Machine Learning",
            "Computer Vision",
            "LLMs",
            "RAG",
            "Cloud AI"
        ]

    def solve(self, problem):
        return ProductionSoftware(
            frontend="Next.js",
            backend="FastAPI",
            cloud="AWS",
            ai="TensorFlow"
        )
```

------------------------------------------------------------------------

## `stack.yml`

``` yaml
languages:
  - Python
  - TypeScript
  - JavaScript
  - Kotlin

frontend:
  - React
  - Next.js
  - Tailwind CSS

backend:
  - FastAPI
  - Flask
  - Node.js

ai:
  - TensorFlow
  - Scikit-Learn
  - MediaPipe
  - Gemini
  - OpenAI

cloud:
  - AWS
  - Firebase
  - Docker

database:
  - PostgreSQL
  - MongoDB
  - MySQL
```

------------------------------------------------------------------------

## Terminal

``` bash
$ help

about
projects
skills
experience
contact
github
linkedin
clear
theme

$ whoami

Full Stack Engineer
AI Engineer
Cloud Developer

Building AI products for real-world problems.

$ sudo hire erasmo

Permission granted.

Opening contact.md...
```

------------------------------------------------------------------------

## `contact.md`

``` md
Email:
montufarbe@gmail.com

LinkedIn:
https://linkedin.com/in/erasmomb

GitHub:
https://github.com/ErasmoMB
```
